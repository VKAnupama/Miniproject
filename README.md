# Password Strength Analyzer

**Project Purpose**

The Password Manager is a web-based application designed to help users generate, analyze, save, and manage passwords securely. It ensures that users can create strong passwords, store them safely in the browser, and access them later only with proper authorization

**Project Features**

### 1.	Home Page
*	Acts as the entry point of the application.
*	Provides options for users to:
-	Generate Password
-	View Vault (to see already saved passwords)

### 2.	Password Generation
*	Users can either:
-	Generate a random strong password using letters, numbers, and symbols.
-	Enter their own password manually.
*	Ensures strong passwords are created easily.
*	After generation, the password is sent to the Password Strength Analyzer.

### 3.	Password Strength Analyzer
*	Evaluates password strength and categorizes it as:
-	Weak – simple or short passwords.
-	Medium – moderate complexity.
-	Strong – long and complex, including uppercase, numbers, and symbols.
*	Helps users understand how secure their password is before saving it.
*	Provides an option to save passwords securely to the vault.

### 4.	Vault (Password Storage)
*	Saves passwords along with website and username.
*	Uses AES-GCM encryption to ensure that saved passwords are secure.
*	Only accessible by entering the master password.
*	Allows users to:
-	View decrypted passwords after authentication.
-	Clear all stored passwords if needed.
*	Data is stored in browser local storage, making it persistent and offline.

### Learning Outcomes

*	Full frontend web development practice with HTML, CSS, and JavaScript.
*	Implementation of encryption 
*	Understanding of local storage, data persistence, and security.
*	Teaches secure password management best practices:
-	Generating strong passwords
-	Analyzing password strength
-	Storing passwords safely

### Limitations
*	Data is only stored locally, so vault is not synced across devices.
*	Local storage is browser-specific. If you switch browsers or computers, vault data is unavailable.
*	Security relies on strong master password. Weak master password can compromise vault security
