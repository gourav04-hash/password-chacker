# Password Strength Checker (Linux Version)

This is a simple application that checks the strength of a given password based on the following criteria:
- Lowercase letters
- Uppercase letters
- Digits
- Special characters
- Minimum length of 8 characters

## How to Use

### Option 1: Running the Python Script

1. **Ensure Python 3 is installed** on your system.
   - You can check if Python is installed by running:

     ```bash
     python3 --version
     ```

   - If Python 3 is not installed, you can install it using the following command (for Ubuntu/Debian-based distributions):

     ```bash
     sudo apt-get update
     sudo apt-get install python3
     ```

2. **Download the `password_checker.py` script**.
   - Clone this repository using `git`:

     ```bash
     git clone https://github.com/gourav04-hash/password-checker.git
     ```

   - Or download the `password_checker.py` file directly from the repository.

3. **Make the script executable (optional)**:
   - You can make the script directly executable from the terminal:

     ```bash
     chmod +x password_checker.py
     ```

4. **Run the script**:
   - Navigate to the directory where `password_checker.py` is saved and run:

     ```bash
     ./password_checker.py
     ```

   - Alternatively, you can run the script using Python directly:

     ```bash
     python3 password_checker.py
     ```

   - When prompted, enter a password to check its strength.

---

### Option 2: Running the Standalone Executable (No Python Required)

1. **Download the Linux Executable**:
   - Download the Linux executable (`password_checker`) from the `dist/` folder of this repository.

2. **Make the Executable File Runnable**:
   - After downloading the `password_checker` executable, navigate to the folder containing the file and run the following command to make it executable:

     ```bash
     chmod +x password_checker
     ```

3. **Run the Executable**:
   - Run the executable from the terminal:

     ```bash
     ./password_checker
     ```

   - When prompted, enter a password to check its strength.

---

## Requirements

- **Python 3.x** (for running the Python script directly)
- **No installation required** for running the standalone executable.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Troubleshooting

- If you encounter issues with running the script or executable, ensure that you have the necessary permissions to execute the files. Use `chmod +x` to make them executable if needed.
- Ensure that Python 3 is installed if you're running the script version.

