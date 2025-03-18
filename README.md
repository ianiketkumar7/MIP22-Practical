# MIP 22 - Advanced Phishing Tool 🚀  

MIP 22 is an **advanced phishing tool** created for **penetration testing** and **security research**. It helps cybersecurity professionals and researchers generate phishing links using **Cloudflared** and other tunneling services to test security awareness and defense mechanisms.

⚠️ **Disclaimer**: This tool is strictly for **educational and security research purposes only**. Using it for illegal activities or unauthorized attacks is against the law and strictly prohibited. Always obtain permission before conducting any security testing.  

## 📥 How to Install MIP 22 on GNU/Linux  
Follow these simple steps to install MIP 22 on your Linux system:  

1️⃣ Open your **terminal** and switch to **root user** (administrator mode):  
```bash
sudo su
```
2️⃣ **Download the tool** from GitHub:  
```bash
git clone https://github.com/makdosx/mip22.git
```
3️⃣ **Give the necessary permissions** to the tool so it can run properly:  
```bash
chmod -R 777 mip22
```
4️⃣ **Enter the tool’s directory**:  
```bash
cd mip22
```
5️⃣ **Run the tool**:  
```bash
bash mip22.sh
```  

## 🚀 How to Use MIP 22  

1️⃣ **Start the tool** by running the command:  
```bash
bash mip22.sh
```
2️⃣ **Choose an option** from the menu. For a simple phishing attack, select Option **1: "Attack Default"**.  
3️⃣ **Select a tunneling service** to create a link (e.g., Cloudflared). Tunneling services help create a secure link between your system and the target.  
4️⃣ **MIP 22 will generate multiple phishing links**, including:  
   > **HTTP URL** (a basic link)  
   > **HTTPS URL** (a secure link with encryption)  
   > **Server URL** (a direct link to your local server)      
5️⃣ **Share the generated phishing link** with the target for security testing.    
6️⃣ **If the target enters their credentials, they will be displayed** in your terminal where MIP 22 is running. This helps ethical hackers and cybersecurity professionals understand how phishing attacks work and train users to recognize them.  

## ⚠️ Troubleshooting (Fixing Common Issues)  

- **Cloudflared is not generating a link?**  
  - Try **exiting** the tool and running the script again.  
- **No internet connection detected?**  
  - Ensure you have a **stable internet connection** before using the tool.  
- **Permission issues while running the script?**  
  - Run the tool in **root mode** using `sudo su` before executing commands.  

## 📌 Important Notes  
✅ **Use this tool responsibly** – It is designed for cybersecurity awareness and ethical hacking purposes only.  
✅ **Always get permission** before conducting penetration testing on any system.  
✅ **Best operating systems** for using this tool: **Kali Linux / Parrot OS / Ubuntu** (These OS are used by cybersecurity professionals).  

## 📜 License  
MIP 22 is an open-source tool meant for ethical hacking and security testing. The **user is responsible for any misuse** of the tool. Always follow legal and ethical guidelines while using it.  

---

🛡️ **Stay safe, practice ethical hacking, and contribute to cybersecurity awareness!** 🔒
