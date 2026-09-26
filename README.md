# 🔐 Week 3 – Password Cracking

**Program:** Cybersecurity Program
**Batch:** B083-Networkwalks
**Modules:** W3-PM1 & W3-PM2
**Date:** September 2026

---

## ⚠️ Liability Disclaimer

All activities documented in this project were performed for educational and authorized cybersecurity training purposes as part of the Networkwalks Cybersecurity Program. The password-cracking activities were performed only on the provided password-protected PDF and within the permitted learning environment.

No unauthorized systems, accounts, or files were targeted.

---

# 📖 Introduction

Password cracking is a cybersecurity technique used to recover or test passwords protecting files and other resources. It helps security professionals understand how password protection works and how different password-recovery techniques can be used in an authorized environment.

In Week 3, I practiced recovering the password of a protected PDF using two different methods. The first method used JTR, while the second method used the Networkwalks Hash Calculator and Password Cracker.

---

# 🎯 Objectives

The main objectives of this week's activities were:

* To understand the basic concept of password cracking.
* To recover the password of a password-protected PDF.
* To practice password recovery using two different methods.
* To understand how a file hash can be used during password-cracking activities.
* To verify the recovered password by successfully unlocking the PDF.
* To document the process and results as part of the cybersecurity training.

---

# 🛠️ Tools Used

| Tool                          | Purpose                                                 |
| ----------------------------- | ------------------------------------------------------- |
| JTR (John the Ripper)         | Password recovery method                                |
| Networkwalks Hash Calculator  | Generate the hash of the protected PDF                  |
| Networkwalks Password Cracker | Perform password cracking using the generated hash      |
| Password-Protected PDF        | File used for the authorized password-recovery exercise |

---

# 🔎 Activities Performed

W3-PM1 – Password Cracking using John the Ripper

🔹 Step 1 – Extract the PDF Hash

The first step in the JTR process is to extract the password hash from the protected PDF.

For a PDF password-cracking workflow, the PDF is processed to obtain its corresponding hash. This hash is then used by John the Ripper during the password-cracking process.


🔹 Step 2 – Check the Extracted Hash

The extracted hash is checked to confirm that the PDF hash has been obtained correctly and is ready to be processed by John the Ripper.

A PDF hash generated for this purpose contains information that allows JTR to perform the password-recovery process.


🔹 Step 3 – Run John the Ripper

The extracted PDF hash is provided to John the Ripper, which attempts to recover the original password using a password wordlist.

JTR compares possible passwords against the hash until a matching password is identified.


🔹 Step 4 – Recover and Verify the Password

After the cracking process, the recovered password is used to open the original protected PDF.

The PDF opens successfully, confirming that the recovered password is correct.

✅ Result

The password of the protected PDF was successfully recovered using the John the Ripper password-cracking process and verified by opening the PDF.

<img width="978" height="837" alt="Screenshot 2026-09-26 152454" src="https://github.com/user-attachments/assets/20d8e884-29f8-40b4-91dc-064132b3f7f5" />


---

# 🌐 W3-PM2 – Password Cracking using Networkwalks Tools

### Objective

To recover the password of the same protected PDF using the Networkwalks Hash Calculator and Password Cracker.

### Step 1 – Generate the PDF Hash

I opened the Networkwalks Hash Calculator using Google Chrome and uploaded the password-protected PDF. The tool generated a hash from the PDF.

<img width="1282" height="887" alt="Screenshot 2026-09-26 154817" src="https://github.com/user-attachments/assets/29343cf3-614c-47b5-97b5-f2697b3283ab" />

---

### Step 2 – Use the Generated Hash

The generated hash was used with the Networkwalks Password Cracker to perform the password-cracking process.

<img width="1835" height="756" alt="Screenshot 2026-09-26 152925" src="https://github.com/user-attachments/assets/42841fb6-81b0-4a1e-9bba-354ddb574622" />

---

### Step 3 – Verify the Recovered Password

After recovering the password, I used it to open the original protected PDF and confirmed that the password was correct.

---

### Result

The password was successfully recovered using the Networkwalks tools and verified by unlocking the protected PDF.

<img width="747" height="827" alt="Screenshot 2026-09-26 154746" src="https://github.com/user-attachments/assets/c8458287-bd64-4cb0-9db4-3536b022c78d" />


---

# 📊 Observation

The two methods demonstrated different approaches to password recovery.

The first method focused on recovering the password through the first password-cracking technique, while the second method involved generating a hash from the protected PDF and using that hash with the Networkwalks Password Cracker.

The successful unlocking of the PDF confirmed that the recovered password was correct.

---

# 📝 Conclusion

Week 3 provided practical experience with password recovery and helped me understand how password-protected files can be analyzed during an authorized security assessment.

I successfully recovered the password of a protected PDF using two different methods and verified the result by unlocking the PDF. The activity also helped me understand the role of hashes in password-cracking processes and the importance of using strong passwords to protect sensitive information.

---

# 👨‍🏫 Mentor
---

Waqas Karim (CCIE)

Thank you for the valuable technical guidance and hands-on learning experience throughout the internship.


---

# 👤 Author
---

Albina Shakil

Cybersecurity Learner B083

LinkedIn: https://www.linkedin.com/in/albina-shakil-3a08952a4/

---


# 📌 Project Information

**Program:** Networkwalks Cybersecurity Program
**Batch:** B083
**Week:** 3
**Modules:** W3-PM1 & W3-PM2
**Topic:** Password Cracking
**Platform:** Windows / Google Chrome
**Purpose:** Educational and Authorized Cybersecurity Training

