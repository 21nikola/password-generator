🔐 Password Generator PRO
A lightweight web-based password generator designed for flexibility and practical usage — especially useful for system administrators who frequently need different types of passwords.

🚀 Features
✅ Generate secure passwords instantly
✅ Adjustable password length (8–32 characters)
✅ Option to include:
Symbols (! @ # $ % &)
Numbers (0–9)

✅ Password strength indicator (Weak / OK / Good / Strong)
✅ Copy password to clipboard with one click
✅ Password history log for quick reference

🧠 Purpose
This tool is built with real-world sysadmin needs in mind.
In many environments, password policies can vary:
Sometimes symbols and numbers are required
Sometimes simpler passwords are needed (for legacy systems, temporary access, etc.)

Because of this, the generator allows:

✅ Enabling/disabling symbols
✅ Enabling/disabling numbers

Additionally, the password history feature helps by:
Keeping track of recently generated passwords
Allowing quick reuse or reference when working across multiple systems
Improving workflow efficiency during repetitive administrative tasks

📂 Project Structure
.
├── index.html        # Main application (HTML, CSS, JS)
├── words.json        # Word list used for password generation

⚙️ How It Works

The app loads a word list from words.json
It generates a password by combining:
Random words
Optional symbols and numbers

The password is trimmed to the selected length
The first letter is capitalized
Strength is calculated based on:
Length
Uppercase letters
Numbers
Special characters
The password is saved in the history list

🖥️ Usage

Open index.html in your browser
Adjust settings:
Choose length using the slider
Enable/disable symbols and numbers

Click Generate
Click Copy to save the password to clipboard
View previously generated passwords in the history section

⚠️ Notes

Passwords are generated locally in the browser (no external API calls)
Clipboard access requires a modern browser
History is stored only in the current session (not persisted)

🔐 Security
Security is a core focus of this project.
✅ Local Generation Only
All passwords are generated directly in the browser. No data is sent to any server or external API.
✅ No Data Exposure
Generated passwords never leave the user's device, reducing the

💡 Ideal For

System administrators
IT support engineers
Developers
Anyone needing fast, customizable password generation

👨‍💻 Author
Nikola 
