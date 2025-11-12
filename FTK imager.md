## Aim
To check whether the hash values of two forensic images differ slightly. Evaluate possible causes and justify whether integrity is compromised using FTK Imager

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

![FTK Imager Verification Output](https://github.com/Krishnabhargav08/End-Semester-Practical/blob/main/images/Screenshot%20(6).png)

![FTK Imager Verification Output](https://github.com/Krishnabhargav08/End-Semester-Practical/blob/main/images/Screenshot%20(2).png)

![FTK Imager Verification Output](https://github.com/Krishnabhargav08/End-Semester-Practical/blob/main/images/Screenshot%20(5).png)

![FTK Imager Verification Output](https://github.com/Krishnabhargav08/End-Semester-Practical/blob/main/images/Screenshot%20(4).png)


## Result
Both the computed and report hash values for **MD5** and **SHA1** matched successfully.  
Therefore, the forensic image integrity was **verified and preserved**.  

---

