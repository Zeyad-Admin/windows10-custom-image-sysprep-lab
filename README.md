# 📘 Windows 10 Custom Image — Sysprep Lab

> 🧪 Creating a deployable Windows 10 reference image using Audit Mode and Sysprep

---

## 🏫 Program
BCIT Technology Support Professional (TSP)

## 🎯 Objective
Build a customized Windows 10 reference virtual machine, install updates and administrative tools, generalize the system using Sysprep, and export the image for deployment.

---

## 🖥️ Environment

| Role | System |
|-------|--------|
| Hyper-V Host | Physical Server |
| Reference VM | Windows 10 Trial |

---

## ⚙️ Tasks Completed

✔ Installed Windows 10 in Hyper-V  
✔ Entered Sysprep Audit Mode  
✔ Installed Windows Updates  
✔ Installed required applications:
- Google Chrome
- RSAT Tools (Server Manager, AD DS, DNS, DHCP)
- Wireshark
- Adobe Reader
✔ Added and formatted secondary 40GB NTFS disk  
✔ Generalized system using Sysprep  
✔ Shutdown for image capture  
✔ Exported VM as backup  

---

## 📚 Key Concepts

### 🔹 Sysprep
System Preparation Tool removes system-specific data (SID, hardware info, logs) to allow cloning.

### 🔹 Audit Mode
Administrative mode that allows customization before OOBE without creating user accounts.

### 🔹 Generalize
Removes unique identifiers so the image can be deployed to multiple machines.

---

## 📸 Screenshots

See `/screenshots` folder for full documentation.

---

## 💼 Skills Demonstrated

- Windows deployment preparation
- Enterprise imaging concepts
- System customization
- Hyper-V administration
- Documentation practices

---

## 🧠 Author
**Zeyad Al Mahmoudi**  
BCIT TSP Program — Canada