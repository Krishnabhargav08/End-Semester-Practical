## Aim
To verify the integrity of a forensic image using **FTK Imager** by comparing cryptographic hash values (MD5 and SHA1) of the acquired image with the original hash to ensure data integrity is preserved.

---

## Procedure
1. Launch **FTK Imager**.  
2. Click on **File → Verify Image…**.  
3. Browse and select the forensic image file (e.g., `integrity.ad1`).  
4. FTK Imager computes the **MD5** and **SHA1** hash values of the image.  
5. It compares these computed hashes with the **report (stored) hash** values.  
6. Observe the verification results:
   - If both hashes match → **Integrity Preserved** 
   - If they differ → **Integrity Compromised** 

---
**Sample Output Screenshot:**


![FTK Imager Verification Output](assets/ftk_verify_results.png)

![FTK Imager Verification Output](assets/ftk_verify_results.png)


## Result
Both the computed and report hash values for **MD5** and **SHA1** matched successfully.  
Therefore, the forensic image integrity was **verified and preserved**.  

---

