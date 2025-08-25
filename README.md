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
Example Run
Enter password length: 8

Choose character set for password: 
1. Digits
2. Letters
3. Special characters
4. Done
Pick a number: 1
Pick a number: 2
Pick a number: 4

Generated Password: a7Gd90Lb

⚙️ Implementation Details

Digits: Built using ASCII loop ('0' to '9').
Letters: Built using ASCII loop ('a' to 'z' and 'A' to 'Z').
Special Characters: Defined manually (!@#$%^&*()-_=+[]{};:,.<>?/|\~`) → contains 30 characters.
Random Selection: Characters picked using Random.nextInt().

📌 Future Enhancements

 Use SecureRandom instead of Random for stronger cryptographic randomness.
 Ensure at least one character from each chosen set is included (strong password rule).
 Add option to generate multiple passwords at once.
 Export generated passwords to a file.
