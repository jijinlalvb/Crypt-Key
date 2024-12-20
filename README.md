# Crypt Key - READ ME 📝

Welcome to **Crypt Key**, a secure message encryption and decryption tool! 🔐

Thank you for choosing **Crypt Key**, a simple and secure tool for encrypting and decrypting messages. 🙏 
This tool allows you to protect your communications with strong encryption, ensuring that only authorized parties can read your messages.

Below is everything you need to know to get started and make the most of the tool.

Currently supported only on **Windows** (.exe).

-----------------------------------------------------------------------

# **Key Features:**
- **Strong Password Validation:** Ensures your password meets security standards (minimum length, uppercase, numbers, and special characters).
- **Password-based Encryption & Decryption:** Securely encrypt your messages with a password, and decrypt them with the same password.
- **Multi-threading:** Encryption and decryption operations are handled in separate threads for faster and more responsive processing.
- **User-friendly Interface:** A colorful and easy-to-use command-line interface with helpful prompts and validations.
- **Customizable Ending Line for Encryption:** Set a custom line to mark the end of your encrypted message input.

-----------------------------------------------------------------------

# **How to Use:**
1. **Running the Application:**
   - Download and run the `Crypt Key.exe` for Windows.
   - Double-click the executable to launch the application.

2. **Choose Mode (Encrypt or Decrypt):**
   - Upon running the application, you will be prompted to choose whether you want to:
     - **Encrypt** a message (type `e`)
     - **Decrypt** a message (type `d`)

3. **Encrypting a Message:**
   - To encrypt a message, you will be asked to input the message you wish to encrypt.
   - You can type your message line by line, and when you are finished, enter your custom **ending line** to stop.
   - <Enter Password> of your choice for encrypting your message. 
   - The application will encrypt your message and display the **encrypted message**, which you can save or share securely.

4. **Decrypting a Message:**
   - To decrypt a message, simply paste the encrypted text when prompted.
   - Enter the password you used during encryption.
   - If the correct password is provided, the **original message** will be revealed.

5. **Enter Password:**
   - A password is required for both encryption and decryption.
   - You will be prompted to enter a password. The password will be validated to ensure it meets the following security requirements:
     - At least 8 characters
     - Includes at least one uppercase letter
     - Contains at least one number
     - Contains at least one special character
   - If your password fails to meet the criteria, you will be prompted to try again or continue with the weak password.

6. **Repeat or Exit:**
   - After encryption or decryption, you can choose to perform another operation by typing `y` or exit the application by typing `n`.

-----------------------------------------------------------------------

# **Important Notes:**

- **Password Security:** Always choose a strong password to ensure the security of your encrypted messages. If you forget your password, the message cannot be decrypted.
- **Encryption Key:** The application uses **Fernet encryption**, which is password-based. The same password used for encryption must be used for decryption.
- **Custom Ending Line:** When encrypting a message, you can set a custom ending line. The message input will stop when this line is entered.
- **Threading:** Encryption and decryption are performed in separate threads, which helps improve processing speed and ensures the tool remains responsive.

-----------------------------------------------------------------------

# **Troubleshooting:**

- **Invalid Token (Decryption Failed):** If decryption fails with an "InvalidToken" error, it typically means the password you entered is incorrect or the encrypted message has been altered. Ensure you are using the correct password.
- **Password Validation Errors:** If your password does not meet the requirements (e.g., too short or missing special characters), the program will prompt you to enter a valid password.
- **Password Re-entry:** If your password is weak or invalid, you can choose to re-enter it, or you can proceed with the weak password if you select 'n' after being warned.

-----------------------------------------------------------------------

# **Security Considerations:**

- **Never share your password.** The strength of encryption depends on the secrecy of your password. Keep your password safe.
- **Backup encrypted messages and passwords.** Losing the password means you cannot decrypt the message, so ensure you save your passwords securely.
- **Ending Line for Encryption:** Be sure to remember the custom ending line used during encryption, as it marks the end of the message input.

-----------------------------------------------------------------------

## Thank You! 🙏
------------------------------------------------------

Thank you for using **Crypt Key**! Your choice to secure your messages is an important step towards privacy and security. We hope you find this tool useful 😊.

------------------------------------------------------

## Stay Updated!
------------------------------------------------------

For updates, new releases, or to contribute to the development of this tool, please visit my GitHub page: 🔗 https://github.com/jijinlalvb 🔗

