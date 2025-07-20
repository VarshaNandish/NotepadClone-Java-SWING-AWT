# 📝 Java Notepad Clone

A simple Notepad clone built using **Java Swing and AWT**. This project replicates the basic functionality of Windows Notepad, including file operations, text editing features, and a custom About window.

---

## 🚀 Features

- 📄 Create, Open, Save, and Print `.txt` files
- ✂️ Edit options: Cut, Copy, Paste, Select All
- 💾 Scrollable and line-wrapped text area
- 🖨️ Print support
- ℹ️ Custom "About Notepad" popup with icons
- ⌨️ Keyboard Shortcuts (Ctrl+N, Ctrl+O, Ctrl+S, etc.)
- 🖼️ Embedded icon images using `ImageIcon`
- 📦 Fully written in Java, platform independent

---

## 🛠️ Tech Stack

- Language: **Java**
- GUI Toolkit: **Swing** and **AWT**
- IDE: Compatible with **NetBeans**, **IntelliJ**, or any Java IDE
- JDK: **Java 8 or later**

---

## 📂 Project Structure

```
src/
└── notepad/
    ├── Notepad.java         # Main Notepad window
    ├── About.java           # About popup window
    └── icons/
        ├── windows.png      # Banner logo
        └── notepad.png      # Icon image
```

---

## 🧑‍💻 How to Run

1. Ensure Java (JDK 8+) is installed.
2. Clone or download the repository.
3. Open the project in NetBeans (or your favorite Java IDE).
4. Set `Notepad.java` as the main class.
5. Run the project. 🎉

---

## 📌 Notes

- You can customize font, themes, and add more features like **Undo/Redo**, **Word Count**, or **Find & Replace**.
- The "About" window loads images from the `icons` folder using `ClassLoader`.

---

## 📄 License

This project is open-source and free to use for learning or modification.

---

## Author

Created by Varsha

Inspired by Notepad in Windows and built as a GUI learning project.
