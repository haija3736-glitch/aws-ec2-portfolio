# My First Cloud Server: AWS EC2 & Nginx Web Server

##  Objective
Successfully provisioned, configured, and deployed a cloud-based Linux server on Amazon Web Services (AWS) to host a public web server.

## 🛠️ Tools & Technologies
- **Cloud Provider:** AWS (EC2, Security Groups)
- **OS:** Ubuntu Linux
- **Web Server:** Nginx
- **Networking:** SSH, HTTP, Port Configuration

## Steps Accomplished
1. **Provisioned an EC2 Instance:** Launched a free-tier Ubuntu Linux virtual machine on AWS.
2. **Configured Security Groups:** Set up custom firewall rules to allow inbound HTTP traffic (Port 80) from anywhere (`0.0.0.0/0`) for web access, and restricted SSH (Port 22) for secure remote management.
3. **Connected to Server:** Accessed the Linux server remotely via terminal.
4. **Deployed Nginx:** Updated system packages and installed the Nginx web server using Linux commands (`sudo apt update` & `sudo apt install nginx`).
5. **Troubleshooting & Verification:** Successfully tested server response using `curl` and resolved browser-forced HTTPS redirect issues to ensure the HTTP site is publicly accessible.

##  Project Screenshots

### 1. Launching EC2 Instance on AWS

 <img width="1863" height="750" alt="Screenshot 2026-10-19 164947" src="https://github.com/user-attachments/assets/522369e8-23de-49eb-b497-8fe7168ce9e7" />

### 2. Configuring Security Groups (Port 80 & Port 22)
<img width="1462" height="486" alt="Screenshot 2026-10-19 170501" src="https://github.com/user-attachments/assets/9d1603c8-0f1b-4758-8c3f-61e670b47af4" />

### 3. Server Response Verification via Windows CMD (`curl`)
<img width="772" height="534" alt="Screenshot 2026-10-19 173729" src="https://github.com/user-attachments/assets/a49ef7ac-c2b1-4155-a451-d5ce15135825" />

### 4. Live Nginx Web Page Running in Browser
<img width="1184" height="354" alt="Screenshot 2026-10-19 173831" src="https://github.com/user-attachments/assets/c8714ef2-dd6e-4da4-93fd-08156bb03c0c" />
