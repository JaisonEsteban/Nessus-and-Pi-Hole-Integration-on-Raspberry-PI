# Installation Guide for Nessus and Pi-hole on Raspberry Pi

## Set Up Pi-hole

1. **Install Pi-hole:**
   - Run the installation script:
     ```bash
     curl -sSL https://install.pi-hole.net | bash
     ```

2. **Configure Pi-hole:**
   - Set up Pi-hole during the installation process. Make sure to use your Pi-hole’s IP address as your DNS server in your network settings.

3. **Access Pi-hole:**
   - Navigate to `http://<your-pi-ip>/admin` to access the Pi-hole dashboard.

## Set Up Nessus

1. **Download Nessus:**
   - Download Nessus for Linux using Curl:
     ```bash
     curl --request GET \
       --url 'https://www.tenable.com/downloads/api/v2/pages/nessus/files/Nessus-10.8.2-raspberrypios_armhf.deb' \
       --output 'Nessus-10.8.2-raspberrypios_armhf.deb'
     ```

2. **Install Nessus:**
   - Install the Nessus package:
     ```bash
     sudo dpkg -i Nessus-10.8.2-raspberrypios_armhf.deb
     ```

3. **Start Nessus:**
   - Start the Nessus service:
     ```bash
     sudo systemctl start nessusd
     ```

4. **Access Nessus:**
   - Open a browser on your computer and navigate to `https://<your-pi-ip>:8834`.
   - Follow the setup instructions to complete the Nessus configuration.

  

