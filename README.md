# 🎤 Speech Assistant

> A modern Windows Forms application that gives voice to your text and converts your speech into written words with ease.

---

## ✨ Key Features

### 🗣️ Speech Tools

**Text-to-Speech Engine**

- 📝 Transform written text into clear, natural speech  
- 🎚️ Adjust speed and volume to your liking  
- ⏯️ Simple and responsive playback controls  
- 💾 Export speech output as WAV files  
- 📄 Open and read text files effortlessly  

**Speech-to-Text Converter**

- 🎙️ Instantly transcribe your voice into text  
- 📋 One-click copy to clipboard  
- 💫 Real-time speech recognition  
- 📥 Save transcriptions directly to your desktop  

---

### 👤 User-Friendly Design

- 🔐 Secure, easy-to-use login system  
- ✉️ Quick registration with email verification  
- 🛡️ Password protection with show/hide option  
- 💽 Data stored securely in a local database  

---

### 🎯 Extra Highlights

- 🎨 Sleek, modern interface  
- ⌨️ Smooth keyboard navigation  
- 📬 Built-in feedback form  
- 📁 Simple file management  
- ⚡ Robust input validation to avoid errors  

---

## 🔧 System Requirements

- 💻 Windows OS  
- 🎯 .NET Framework 4.7.2  
- 📦 Microsoft SQL Server LocalDB  
- 🗣️ System.Speech library support  
- 🛠️ Visual Studio 2019 or later (for development)  

---

## 🚀 Getting Started

1. 📥 Clone this repository  
2. 🔓 Open the solution in Visual Studio  
3. 📦 Ensure SQL Server LocalDB is installed  
4. ⚙️ Set up the database connection  
5. 🏃‍♂️ Build and run the application!  

---

## 💾 Database Configuration

The app uses a SQL Server LocalDB database (`data.mdf`) with an `admin` table:

```sql
CREATE TABLE admin (
    email VARCHAR(100),
    username VARCHAR(50),
    _password VARCHAR(50),
    date_created DATETIME
);
