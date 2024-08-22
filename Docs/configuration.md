# Configuration Guide for Nessus and Pi-hole on Raspberry Pi

## Configure Pi-hole

1. **Access the Pi-hole Dashboard:**
   - Open a web browser and navigate to `http://<your-pi-ip>/admin`.

2. **Log In:**
   - Use the admin password set during installation to log in.

3. **Configure DNS Settings:**
   - Go to **Settings** > **DNS**.
   - Ensure that Pi-hole is set to be your network’s DNS server. You can enter upstream DNS servers like Google DNS (`8.8.8.8` and `8.8.4.4`) or Cloudflare (`1.1.1.1`).

4. **Configure Block Lists:**
   - Go to **Settings** > **Block Lists**.
   - Add or remove block lists according to your needs.

5. **Configure Clients:**
   - To configure devices on your network to use Pi-hole, change their DNS settings to point to the Pi-hole IP address.

6. **Additional Configuration:**
   - Explore other settings like **Whitelist**, **Blacklist**, and **Query Log** for fine-tuning Pi-hole’s behavior.

## Configure Nessus

1. **Access Nessus:**
   - Open a web browser and navigate to `https://<your-pi-ip>:8834`.

2. **Set Up Nessus:**
   - Create an account and log in.
   - Follow the on-screen instructions to configure Nessus. This includes setting up the Nessus Home or Professional license if required.

3. **Update Nessus Plugins:**
   - After initial setup, Nessus will download and update its plugins. This may take some time.

4. **Create Scan Policies:**
   - Go to **Policies** and create scan policies based on your network and security requirements.

5. **Configure Scans:**
   - Set up new scans by going to **Scans** and creating scan jobs. Configure the targets and schedule them according to your needs.

6. **Review and Analyze Reports:**
   - Once scans are complete, review the results under **Reports**. Analyze the vulnerabilities and take necessary actions to mitigate risks.

