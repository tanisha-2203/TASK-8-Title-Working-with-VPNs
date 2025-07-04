# TASK-8-Title-Working-with-VPNs

OS used: linux

1. Open terminal to install Proton VPN
2. Download app package: wget https://repo.protonvpn.com/debian/dists/stable/main/binary-all/protonvpn-stable-release_1.0.8_all.deb
3. Install the Proton VPN repository containing the app. Enter:sudo dpkg -i ./protonvpn-stable-release_1.0.8_all.deb && sudo apt update
4. If you want to check the repo package integrity, you can check its checksum with the following command:echo "0b14e71586b22e498eb20926c48c7b434b751149b1f2af9902ef1cfe6b03e180 protonvpn-stable-release_1.0.8_all.deb" | sha256sum --check -
5. Install the app. Run: sudo apt install proton-vpn-gnome-desktop
6. Open the VPN client from your applications menu.
7. Log in with your account credentials.
8. Select a server location (preferably the closest one) and click "Connect."
9. Verify Your IP Address Has Changed:
    Open a web browser and go to whatismyipaddress.com.
    Note the displayed IP address; it should be different from your original IP.
10. Browse a Secure Website:
    Visit a website that starts with "https://" (e.g., https://www.example.com).
    Look for a padlock icon in the address bar to confirm the connection is secure.
11. Disconnect the VPN:
    Go back to the VPN client and click "Disconnect."
    Check your IP address again on whatismyipaddress.com to see your original IP.
    



