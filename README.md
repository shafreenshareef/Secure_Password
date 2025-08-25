# Secure_Password
🔐 Java Password Generator

This project is a **Password Generator** written in Java.  
It allows the user to create strong random passwords by choosing from different character sets (**digits, letters, and special characters**) and specifying the desired length.

🚀 Features
- User selects password length.
- Menu to include:
  - ✅ Digits (0–9)
  - ✅ Letters (a–z, A–Z)
  - ✅ Special Characters (!@#$%^&*...)
- Uses **ASCII ranges** (loops) to build digits and letters dynamically.
- Random password generation using Java's `Random` class.
- Prevents generation if no character set is selected.
