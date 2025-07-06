
# Bash-user-group-manager
🔧 Bash-Based User & Group Management Tool

A lightweight and interactive **user & group management system** built entirely using **Bash scripting** and **Whiptail** dialog boxes. This tool provides a simple, menu-driven interface for performing common Linux administrative tasks directly from the terminal.

---

## 📋 Features

* ✅ Add, modify, and delete users
* ✅ Add, modify, and delete groups
* 🔐 Lock and unlock (disable/enable) user accounts
* 🔄 Change user passwords
* 📋 View a list of users and groups
* 🛡️ Root privilege check to ensure secure execution
* 💡 Whiptail-based menu for ease of use
* 📦 No external dependencies — uses core Linux utilities

---

## 📸 Demo (Optional)

![Screenshot (243)](https://github.com/user-attachments/assets/dd0be6c9-5f89-4ae0-9f92-bf661fef0346)

---

## 📂 How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/user-group-management.git
   cd user-group-management
   ```

2. **Run the script as root:**

   ```bash
   sudo ./menu_project.sh
   ```

3. **Use the interactive menu to manage users and groups.**

---

## 🛠️ Technologies Used

* **Bash**
* **Whiptail**
* Linux core tools: `useradd`, `groupadd`, `passwd`, `usermod`, `awk` etc.

---

## 📌 Notes

* The script **must be run as root** or using `sudo`.
