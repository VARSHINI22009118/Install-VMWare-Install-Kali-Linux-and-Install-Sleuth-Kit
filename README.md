# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: VARSHINI S A
### Reg No: 212222100059
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version

## PROGRAM:

## OUTPUT:
**VIRTUAL BOX:**
![Screenshot 2025-06-04 234729](https://github.com/user-attachments/assets/bf9f3485-5ee4-4f12-b025-85d4cd6f9aef)


**KALI LINUX:**
![Screenshot 2025-06-04 235046](https://github.com/user-attachments/assets/dd2b9722-fce0-48f9-85bb-501be77da170)


**SLEUTH-KIT:**
![Screenshot 2025-06-04 234952](https://github.com/user-attachments/assets/fc5006de-8ca7-4b43-a50e-d0b36e24918e)


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
