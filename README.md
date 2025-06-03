Cyber Security Internship - Task 4
Firewall Setup and Usage (Windows)

Steps Followed:

1. Opened Windows Defender Firewall from the Start menu.

2. Clicked on "Advanced Settings" to open Windows Defender Firewall with Advanced Security.

3. Clicked on "Inbound Rules" in the left panel.

4. Created a new rule to BLOCK inbound traffic on port 23 (Telnet):
   - Selected "Port"
   - Chose "TCP" and entered port 23
   - Selected "Block the connection"
   - Applied to all profiles (Domain, Private, Public)
   - Named the rule: "Block Telnet (Port 23)"

5. Tested the rule by observing that connection to port 23 was blocked.

6. Created another new rule to ALLOW traffic on port 22 (SSH):
   - Selected "Port"
   - Entered port 22
   - Selected "Allow the connection"
   - Applied to all profiles
   - Named the rule: "Allow SSH (Port 22)"

7. Deleted the block rule for port 23 to restore the original firewall state.

8. Took screenshots of each step as proof of configuration.
![Screenshot (96)](https://github.com/user-attachments/assets/9e3dc370-2794-47ad-a11a-b30765405d33)
![Screenshot (95)](https://github.com/user-attachments/assets/b7eea1a1-afca-415f-9bbb-936dfe406832)
![Screenshot (94)](https://github.com/user-attachments/assets/04cc5687-da70-41a0-9dd8-31f34e85261d)
![Screenshot (93)](https://github.com/user-attachments/assets/793efd68-1e92-4063-b3d7-163371f2f223)

9. Uploaded the screenshots and this text file to a GitHub repository.

Summary:
A firewall filters traffic by blocking or allowing connections based on rules. In this task, I learned how to create rules for specific ports to secure network access.
