# task-3
Basic Vulnerability Scan

## Steps Performed

1. **Installed Vulnerability Scanner**

   * Installed OpenVAS or Nessus Essentials.
   * Completed setup and ensured the web interface was running.

2. **Configured Scan Target**

   * Set the target as the machine IP: **`172.20.51.9`**.

3. **Started a Full Vulnerability Scan**

   * Chose the “Full Scan” policy to cover all services and software.
   * Launched the scan and monitored progress.

4. **Waited for Scan Completion**

   * Duration: 30–60 minutes depending on system size and services running.

5. **Reviewed Scan Report**

   * Analyzed the results.
   * Checked each vulnerability’s severity rating (Low, Medium, High, Critical).

6. **Researched Fixes/Mitigations**

   * Looked up patching instructions or configuration changes for the findings.
   * Example fixes: update OS, close unused ports, uninstall outdated software.

7. **Documented Critical Vulnerabilities**

   * Focused on **High** and **Critical** findings.
   * Recorded descriptions, CVSS scores, and remediation steps.

8. **Screenshots**

   * Captured screenshots of the scan dashboard and sample vulnerabilities for documentation.

---

## Example Findings (Sample)

* **Outdated Windows Update** → Apply latest OS patches.
* **Weak SMB Configuration** → Disable SMBv1 protocol.
* **Open Port 23 (Telnet)** → Close or replace with SSH.
* **Outdated Browser Plugins** → Update or remove unused plugins.
