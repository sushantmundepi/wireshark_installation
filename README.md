# wireshark_installation
wireguard installation for ubuntu


Step 1: Update Package List

    sudo apt-get update

Step 2: Install Wireshark
    
    sudo apt-get install wireshark

Step 3: Configure Wireshark for Non-superusers
During the installation, select "Yes" to enable non-superusers to capture packets.

Step 4: Add User to Wireshark Group ( Replace <username> with your actual username. )
     
    sudo usermod -aG wireshark <username>

Step 5: Restart System

Step 6: Launch Wireshark
     
    wireshark
