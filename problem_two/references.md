# Problem 2 – References and Research Notes

This file gathers the material that was checked while completing  
**Problem 2: Fractional Parts of Cube Roots**.  
The main aim was to understand where the SHA-256 constants come from and to
ensure that the values calculated in the notebook matched the official ones.

---

## Primary Source

### **FIPS 180-4 – Secure Hash Standard (NIST)**  
This was the main reference used for the problem.  
Section **4.2.2** explains how the SHA-256 constants are formed using the
fractional parts of the cube roots of the first 64 primes.  
The table at the bottom of page 11 was used when comparing the final list of
hexadecimal constants.

Link: https://doi.org/10.6028/NIST.FIPS.180-4

---

## Supporting Material

### **NumPy Documentation**  
Used for checking how NumPy handles floating point operations, array types
and conversions to 32-bit unsigned integers.  
This helped confirm that the approach used for extracting the fractional parts
was consistent and precise enough for the problem.

https://numpy.org/doc

---

### **General SHA-256 Information (Cross-Check Only)**  
A second source was used purely for confirming that the 64 SHA-256 constants
matched what is commonly listed elsewhere.  
This was only for reassurance and did not replace the official standard.

Wikipedia: https://en.wikipedia.org/wiki/SHA-2

---

## Additional Notes

- All cube-root values were calculated directly in Python using NumPy rather
  than copied from any source.
- The final 64 constants produced in the notebook matched the FIPS 180-4 table
  exactly.
- Only stable and recognised references were used, with the standard itself
  guiding the entire approach.

---

