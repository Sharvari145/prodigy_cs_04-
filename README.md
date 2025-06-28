# prodigy_cs_04-
🔍 Keylogger in Python – Theory-Based Project

This project demonstrates the **theoretical concept and practical implementation** of a keylogger using Python's `pynput` library. A keylogger is a program designed to monitor and record each keystroke made on a computer keyboard.



📘 Objective

The main aim of this project is to **understand how keystroke capturing works** using Python, for academic and research purposes. It highlights the use of **keyboard listeners** and file operations in real-time logging systems.



🧠 Concept

A **keylogger** works by using a background process that listens to all keyboard events. Each key pressed by the user is captured and logged. This can include alphanumeric characters as well as special keys (like Enter, Space, Shift, etc.).

The `pynput.keyboard` module is used to:

* Monitor key presses in real-time
* Differentiate between character keys and special keys
* Record keystrokes into a text file for analysis



⚙️ Working Principle

1. A listener is set up to monitor all keypress events.
2. When a key is pressed:

   * If it is a character key (like 'a', '1', etc.), it is recorded directly.
   * If it is a special key (`Enter`, `Backspace`, etc.), it is logged with appropriate labels.
3. The captured keystrokes are continuously written to a file for later review.
4. The program exits gracefully when the `ESC` key is pressed.



 🧪 Applications (Educational Context)

* Demonstrates **event handling** in Python.
* Shows practical use of **file handling** and **keyboard monitoring**.
* Can be extended to study **data privacy** and **ethical hacking techniques** in cybersecurity courses.



⚠️ Ethical Use

This code is intended strictly for educational purposes. Unauthorized use on systems without user consent is a violation of privacy laws and ethical guidelines.

