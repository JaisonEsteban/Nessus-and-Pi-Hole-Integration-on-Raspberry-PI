# Usage Guide for Nessus and Pi-hole on Raspberry Pi

## Using Pi-hole

1. **Monitor DNS Queries:**
   - Access the Pi-hole dashboard at `http://<your-pi-ip>/admin`.
   - View real-time statistics and query logs to monitor DNS traffic.

2. **Manage Block Lists:**
   - Add new block lists or update existing ones through the **Settings** > **Block Lists** menu.

3. **Whitelist/Blacklist Domains:**
   - Use the **Whitelist** and **Blacklist** sections to allow or block specific domains.

4. **Check Client Activity:**
   - Go to **Network** to see which devices are using Pi-hole for DNS and review their activity.

5. **Troubleshoot Issues:**
   - If you experience issues, check the **Query Log** for detailed information and ensure that Pi-hole is correctly set as the DNS server on your network.

## Using Nessus

1. **Run Scans:**
   - Go to **Scans** > **New Scan** to set up and execute vulnerability scans.
   - Choose a scan policy and configure the target systems.

2. **Review Scan Results:**
   - After scans are complete, review results under **Reports**.
   - Analyze vulnerabilities, their severity, and suggested remediation steps.

3. **Schedule Regular Scans:**
   - Set up recurring scans to keep track of vulnerabilities over time. Go to **Scans** > **Schedule** to create a scan schedule.

4. **Update Nessus Regularly:**
   - Ensure Nessus is up to date by regularly checking for plugin updates and applying them.

5. **Generate Reports:**
   - Use the **Reports** section to generate and export detailed reports of your scan results for documentation or compliance purposes.

