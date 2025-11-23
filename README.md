# 🧪 Lab Instructions — 2.3 Using Directories and Listing Files (LPI Linux Essentials)

---

>💬 **Tip:** Paste this study guide into ChatGPT and ask for **more instructions** by specifying:  
>- “Provide step-by-step lab instructions for this objective.”  
>- “Include which Linux distro to use (Debian/Ubuntu or RHEL/Fedora).”  
>- “Show examples of installing, verifying, and managing desktop and server applications.”  
>- “Include minimal command-line practice for package management and development tools.”  
>- “Focus only on what is most important for passing the LPI Linux Essentials exam.”  

>This will prompt ChatGPT to give **practical, exam-focused lab steps** for each section.

---

## 1️⃣ Verify Your Current Directory
- Run: `pwd`
- Confirm you're in your home directory.  
  ✔️ Expected: `/home/yourname`

---

## 2️⃣ Practice Listing Files
### Basic listing
- Run: `ls`
- Observe file names.

### Long listing
- Run: `ls -l`
- Look at permissions, owner, group, size, timestamp.

### Show hidden files
- Run: `ls -a`
- Confirm files starting with `.` appear (ex: `.bashrc`).

---

## 3️⃣ Navigate Using `cd`
### Move into a directory
- Run: `cd Documents` (or any directory you have)
- Verify with `pwd`.

### Move up one level
- Run: `cd ..`
- Confirm location changed.

### Return home
- Run: `cd ~`
- Verify with `pwd`.

### Return to previous directory
- Run: `cd -`
- Notice it toggles between directories.

---

## 4️⃣ Practice Absolute vs. Relative Paths
### Absolute path
- Run: `cd /etc`
- Confirm with `pwd`.

### Relative path
- From `/etc`, run: `cd ../usr/bin`
- Verify path changed correctly.

---

## 5️⃣ Recursive Listings
- Run: `ls -R /etc`
- Observe recursive directory → subdirectory → file structure.

---

## 6️⃣ Identify Special Directories
### Current directory
- Run: `ls -l .`

### Parent directory
- Run: `ls -l ..`

---

## 7️⃣ Confirm Home Directory Behavior
- Run: `echo $HOME`
- Run: `cd $HOME`
- Run: `pwd`
- Ensure all match.

---

## 8️⃣ Mini Navigation Drill
1. `cd /var/log`  
2. `ls -l`  
3. `cd ..`  
4. `ls -a`  
5. `cd ~`  
6. `ls -R Documents` (or any folder you have)

✔️ If you complete these smoothly, you understand Objective 2.3.
