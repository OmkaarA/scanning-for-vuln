# Introductory Vulnerability Assessment using Nessus Essentials

This project demonstrates a beginner-level vulnerability assessment of a local PC using **Nessus Essentials**. The aim was to gain hands-on experience with vulnerability scanning and understand common security risks found in everyday computer systems.

---

## 🧠 Objective

To develop an introductory understanding of vulnerability assessments and identify typical security issues on a personal computer.

---

## 🛠 Tasks Performed

1. **Installed Nessus Essentials**
   - Downloaded the installer from the Tenable website.
   - Set up the Nessus environment and completed activation using the free license.
<img width="1440" alt="Screenshot 2025-05-29 at 12 57 21" src="https://github.com/user-attachments/assets/738df96f-f658-452b-8088-4d44acac504e" />


2. **Configured the Local Machine as Scan Target**
   - Used `localhost` / local IP address as the scan target.
<img width="1434" alt="4" src="https://github.com/user-attachments/assets/14edcd7e-f189-4743-8e0b-70fc4a006800" />



3. **Initiated a Full Vulnerability Scan**
   - Launched a full system scan with default configurations.
<img width="1434" alt="3" src="https://github.com/user-attachments/assets/d4ab6afd-c219-421b-ac13-b6b0ee7fda30" />



4. **Waited for the Scan to Complete**
   - Scan duration: ~45 minutes (may vary based on system specs and settings).

5. **Reviewed the Report**
   - Identified several vulnerabilities with varying severity levels.
<img width="1432" alt="Screenshot 2025-05-29 at 12 36 04" src="https://github.com/user-attachments/assets/e2bb12c5-8d10-4158-be1e-25f781158bff" />
<img width="1437" alt="2" src="https://github.com/user-attachments/assets/60e35d92-1d98-4962-8423-f9985ebdd50c" />



6. **Researched Fixes or Mitigations**
   - Focused on critical and high-severity issues.
   - Explored official documentation and security forums for solutions.

7. **Documented Critical Vulnerabilities**
   - Example: Outdated version of **Google Chrome** detected.
     - Risk: Exposed to publicly known exploits.
     - Mitigation: Updated Chrome to the latest stable version.
<img width="1430" alt="1" src="https://github.com/user-attachments/assets/38bb682c-7b27-4738-b243-af02dd93d58d" />




8. **Captured Screenshots Throughout**
   - Key steps and findings were visually documented.

---

## 🔍 Key Vulnerability Highlight

**Vulnerability:** Outdated version of Google Chrome  
**Severity:** Critical
**Description:** Known exploits in older versions can allow arbitrary code execution or security bypass.  
**Fix Applied:** Updated to the latest version of Google Chrome via the browser's update manager.

---


## 📚 Learnings & Takeaways

- Setting up vulnerability scanners like Nessus is straightforward with proper guidance.
- Many systems, even freshly installed ones, may have high or medium severity issues.
- Regular updates and patching are vital for system security.
- Understanding CVEs and their implications helps prioritize risks effectively.

---

## ✅ Next Steps (Future Improvements)

- Compare results with other tools like **OpenVAS**.
- Perform scans on virtual machines with intentionally vulnerable setups (e.g., Metasploitable).
- Explore scripting and automation of vulnerability scans.

---

## 📝 License

This project is licensed under the [MIT License](LICENSE) — feel free to use, share, and modify with attribution.

---

> **Disclaimer:** This assessment was done on a personal system in a controlled environment. Always obtain proper authorization before scanning networks or devices you do not own.
