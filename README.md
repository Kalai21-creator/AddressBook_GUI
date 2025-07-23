
# 📇 Address Book App

A simple, clean, and interactive **Address Book GUI application** built with Python's `tkinter`. Easily add, edit, delete, and search contacts with basic email and phone validation.

---

## 🖼️ Features

- 🆕 Add new contacts
- ✏️ Edit existing contacts
- 🗑️ Delete contacts with confirmation
- 🔍 Search contacts by name
- 🧹 Clear fields automatically after use
- 🧠 Input validation (Phone = 10 digits, Email format check)
- 💾 Persistent data storage using `contacts.json`
- 🟥 Highlights contact in red before deletion confirmation

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.x installed on your machine.

### 📦 Install

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/address-book-app.git
    cd address-book-app
    ```

2. Run the app:
    ```bash
    python address_book.py
    ```

---

## 🖥️ GUI Overview

| Function     | Description                       |
|--------------|-----------------------------------|
| Add Contact  | Fills input fields and stores new contact |
| Edit Contact | Select from the list, modify fields, then "Save Edit" |
| Delete       | Highlights selected contact and asks for confirmation |
| Search       | Prompts for name and shows matches |
| Show All     | Displays all saved contacts       |

---

## 🗃️ File Structure

address-book-app/
│
├── contacts.json # Auto-created: stores your contacts
├── address_book.py # Main application script
└── app_icon.ico # (Optional) App icon for the window
---

## 💡 Customization

- **App Icon**: Add an `app_icon.ico` file in the same directory to set a custom window icon.
- **Styling**: You can modify background colors, fonts, and themes in the code.

---

## 🔐 Data Privacy

All contact data is stored **locally** in `contacts.json`. No external servers are involved.

---

## 📜 License

This project is open source under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Built using Python's `tkinter` standard GUI library.  
Inspired by the need for a clean and beginner-friendly contact manager.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

