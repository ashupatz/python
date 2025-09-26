# 📘 Install Python on Windows (Latest Version)

### **Step 1: Download Python**

1. Open a browser and go to the official Python downloads page:
   👉 [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
2. Click **Download Python (Latest Version)**.
   *(Example: "Download Python 3.13.7")*
   This downloads the **Windows Installer (.exe)**.

---

### **Step 2: Run the Installer**

1. Locate the installer file in your **Downloads** folder (e.g., `python-3.13.7-amd64.exe`).
2. Double-click to run it.
3. On the installation screen:

   * ✅ Check **“Add Python to PATH”** (important).
   * Click **Customize Installation** (optional, if you want to choose features).
   * Otherwise, click **Install Now**.

---

### **Step 3: Verify Installation**

1. Open **Command Prompt** (`Win + R`, type `cmd`, press Enter).
2. Type:

   ```sh
   python --version
   ```

   or

   ```sh
   py --version
   ```

   You should see something like:

   ```
   Python 3.13.7
   ```

---

### **Step 4: Set Environment Variables Manually (if needed)**

*(Skip this if you checked “Add Python to PATH” during install.)*

1. Open **Start Menu**, search for **Environment Variables**, and select
   **Edit the system environment variables**.
2. In the **System Properties** window, click **Environment Variables**.
3. Under **System variables**, find **Path** → click **Edit** → **New**.
4. Add the following paths (adjust version number if needed):

   * `C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python312\`
   * `C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python312\Scripts\`
5. Click **OK** → **OK** → **OK** to close all windows.

---

### **Step 5: Test Environment Variables**

1. Open a new **Command Prompt**.
2. Type:

   ```sh
   python
   ```

   This should open the Python REPL.
3. Type:

   ```python
   print("Hello, Python!")
   ```

   You should see:

   ```
   Hello, Python!
   ```

---
