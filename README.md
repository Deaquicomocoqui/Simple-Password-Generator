# 🔐 Password Generator Web GUI

A modern, secure web-based password generator with a beautiful interface!

## 📋 What You Need

1. **Python 3.6 or higher** (check with: `python --version` or `python3 --version`)
2. **Flask** (we'll install this)

## 🚀 Quick Start Guide

### Step 1: Install Flask

Open your terminal/command prompt and run:

```bash
pip install flask
```

Or if you're using Python 3:

```bash
pip3 install flask
```

### Step 2: Run the Application

Navigate to the folder containing these files, then run:

```bash
python password_web_app.py
```

Or:

```bash
python3 password_web_app.py
```

### Step 3: Open Your Browser

You should see output like:
```
🔐 Password Generator Web GUI
==================================================
Starting server...
Open your browser and go to: http://127.0.0.1:5000
Press CTRL+C to stop the server
==================================================
```

Open your web browser and go to: **http://127.0.0.1:5000**

### Step 4: Generate Passwords!

- Use the sliders to customize your password requirements
- Click "Generate Password" to create a new password
- Click "Copy" to copy it to your clipboard
- View the composition stats at the bottom

## 📁 File Structure

```
password-generator/
├── password_web_app.py    # Main Flask application
└── templates/
    └── index.html         # Web interface
```

## ⚙️ Features

- ✅ Customizable password length (8-64 characters)
- ✅ Control minimum requirements for each character type
- ✅ Beautiful, modern interface
- ✅ One-click copy to clipboard
- ✅ Real-time password composition statistics
- ✅ Secure random generation
- ✅ Mobile-friendly design

## 🛑 Stopping the Server

Press `CTRL + C` in the terminal where the server is running.

## 🔧 Troubleshooting

**Problem:** "Module not found: flask"
**Solution:** Install Flask with: `pip install flask`

**Problem:** "Port 5000 is already in use"
**Solution:** Either stop the other program using port 5000, or change the port in `password_web_app.py` (last line, change 5000 to 5001 or another number)

**Problem:** Can't connect to http://127.0.0.1:5000
**Solution:** Make sure the server is running (you should see the startup message in terminal)

## 🔒 Security Notes

- This generator uses Python's `random` module, which is suitable for most purposes
- For cryptographic applications, consider using Python's `secrets` module instead
- Never share or store passwords in plain text
- Use a password manager to securely store generated passwords

## 💡 Tips

- Aim for passwords 16+ characters for maximum security
- Include at least one of each character type
- Use unique passwords for each account
- Consider using a passphrase for memorability

---

Enjoy your secure password generation! 🎉
