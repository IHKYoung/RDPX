# RDP Wrapper Installer and Autoupdater v1.3 

**Author:**  IHKYoung (2024-12-17) base on asmtron's work
**Contributors:** asmtron, sebaxakerhtc, affinityv

---

## 🎯 **Description**  

The **RDP Wrapper autoupdater** automatically installs and updates RDP Wrapper with the latest `rdpwrap.ini` file.  
It first checks the official `rdpwrap.ini` and uses community-contributed(sebaxakerhtc, affinityv) sources if needed.  

---

## ⚙️ **Options**  

| Option       | Description                                               |
| ------------ | --------------------------------------------------------- |
| `-log`       | Redirect display output to `autoupdate.log` file.         |
| `-taskadd`   | Add autorun of `autoupdate.bat` on system startup.        |
| `-taskremove`| Remove autorun of `autoupdate.bat` from system startup.   |

---

## 🛠️ **Installation Steps**  

### Step 1: Create the Installation Directory  
Create the following directory (usually located at `C:\Program Files\RDP Wrapper`):  

```plaintext
%ProgramFiles%\RDP Wrapper
```

⚠️ **Important:**  
- Do **not** use other directories for installation.  
- Use **only**: `%ProgramFiles%\RDP Wrapper`.  


### Step 2: Extract the Autoupdater Files  
Download the RDPX and extract all files and folders into:  

```plaintext
%ProgramFiles%\RDP Wrapper
```

### Step 3: Run the Autoupdater  
To install or update the RDP Wrapper, execute the `autoupdate.bat` file as **Administrator**:

```plaintext
%ProgramFiles%\RDP Wrapper\autoupdate.bat
```
