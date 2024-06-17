
# OpenVPN GUI Setup on Doprax

This guide will help you set up and use the OpenVPN Web GUI on Doprax, 

## Overview

After deploying the OpenVPN Web GUI using the one-click installation from Doprax's App Market, follow these steps to log in and generate certificates for your devices.

## Using OpenVPN Web GUI

1. **Log in to Your VM**

   After logging in to your VM via SSH or "Terminal", you will see the OpenVPN admin credentials displayed in the terminal. These credentials are automatically generated and added to your `.bashrc` file during the setup process.

   Example:
   ```
   OpenVPN Admin Credentials
   Username: admin_XXXX
   Password: XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
   To remove this msg, remove the lines in ~/.bashrc
   ```

2. **Access OpenVPN Web Interface**

Open your web browser and navigate to `http://<vm-ip>:8080/`. Replace `<vm-ip>` with the actual IP address of your VM.

3. **Log in to the Web Interface**

Use the admin credentials displayed in the terminal to log in to the OpenVPN Web GUI.

4. **Create and Download Certificates**

- Go to the "Certificates" section in the OpenVPN Web GUI.
- Click on the "New Certificate" button to create a new certificate for your device.
- Once the certificate is created, click on the certificate name to download it.

### Note

- If you wish to remove the displayed OpenVPN admin credentials from the `.bashrc` file, you can manually delete the relevant lines from the file.

By following these steps, you will have a fully functional OpenVPN Web GUI deployed on your Doprax VM, enabling you to manage VPN connections and certificates easily.
