# 🔐 Password Generator PRO

A lightweight web-based password generator designed for flexibility and practical usage — especially useful for system administrators who frequently need different types of passwords.

---

## 🚀 Features

- ✅ Generate secure passwords instantly  
- ✅ Adjustable password length (8–32 characters)  
- ✅ Option to include:
  - Symbols (! @ # $ % &)
  - Numbers (0–9)  
- ✅ Password strength indicator (Weak / OK / Good / Strong)  
- ✅ Copy password to clipboard with one click  
- ✅ Password history log for quick reference  

---

## 🧠 Purpose

This tool is built with real-world sysadmin needs in mind.

In many environments, password policies can vary:

- Sometimes **symbols and numbers are required**
- Sometimes **simpler passwords are needed** (legacy systems, temporary access, etc.)

Because of this, the generator allows:

- ✅ Enabling/disabling symbols  
- ✅ Enabling/disabling numbers  

Additionally, the password history feature helps by:

- Tracking recently generated passwords  
- Allowing quick reuse across multiple systems  
- Improving efficiency in repetitive administrative tasks  

---

## 📂 Project Structure
.
├── index.html   # Main application (HTML, CSS, JS)
├── words.json   # Word list for password generation

## ⚙️ How It Works

- Loads a word list from `words.json`  
- Generates a password using:
  - Random words  
  - Optional symbols and numbers  
- Trims password to selected length  
- Capitalizes the first letter  
- Calculates strength based on:
  - Length  
  - Uppercase letters  
  - Numbers  
  - Special characters  
- Saves the password in the history list  

---

## 🖥️ Usage

1. Open `index.html` in your browser  
2. Adjust settings:
   - Choose length using the slider  
   - Enable/disable symbols and numbers  
3. Click **Generate**  
4. Click **Copy** to copy the password  
5. View previous passwords in the history section  

---

## ⚠️ Notes

- Passwords are generated locally in the browser (no external API calls)  
- Clipboard access requires a modern browser  
- History is stored only in the current session (not persistent)  

---

## 🔐 Security

Security is a core focus of this project.

- ✅ **Local Generation Only**  
  Passwords are generated entirely in the browser

- ✅ **No Data Exposure**  
  No data is sent to external servers or APIs  

- ✅ **Session-Based History**  
  Data is not stored permanently and is cleared on refresh  

- ✅ **Privacy-First Approach**  
  Passwords never leave the user's machine  

---

## 💡 Ideal For

- System administrators  
- IT support engineers  
- Developers  
- Anyone needing fast and customizable password generation  

---

## 👨‍💻 Author

**Nikola Miščević**
