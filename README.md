

# 🔐 Password Generator

## 🌟 Overview

This Python project is a **simple yet powerful password generator** that creates secure and customizable passwords based on user-defined criteria. It ensures strong password creation suitable for various applications by allowing users to specify length and inclusion of uppercase letters and special symbols.

## 🚀 Features

- **Customizable Password Length**: Choose any length greater than 0.
- **Uppercase Letters**: Optionally include uppercase letters for added strength.
- **Special Symbols**: Add complexity by including special symbols.
- **Secure Random Generation**: Utilizes Python's `secrets` module to create secure random passwords.

## 🛠️ Getting Started

To use this password generator, ensure you have **Python** installed on your machine. You can then run the script in your terminal or command prompt.

### 📋 Prerequisites

- Python 3.x
- Basic understanding of running Python scripts

### 📥 Installation

1. Clone or download the repository.
2. Navigate to the project directory in your terminal.

   ```bash
   git clone <repository-url>
   cd password-generator
   ```

3. Run the script:

   ```bash
   python password_generator.py
   ```

## 🖥️ Usage

When you run the script, you'll be prompted to enter:

1. **Desired Length**: Enter a number greater than 0 for the password length.
2. **Include Symbols**: Type `yes` or `no` to indicate whether to include special symbols.
3. **Include Uppercase Letters**: Type `yes` or `no` to indicate whether to include uppercase letters.

### 💡 Example

```plaintext
Enter the desired length of the password: 12
Include symbols? (yes/no): yes
Include uppercase letters? (yes/no): yes
Generated Password: J!4h8Zw@2kM3
Specifications: Uppercase: True, Symbols: True
```

## 📖 Code Explanation

The core functionality of the password generator is built around three main functions:

- **`containsUpper(password: str) -> bool`**: Checks if the password contains any uppercase letters.
  
- **`containsSymbols(password: str) -> bool`**: Checks if the password includes special symbols.

- **`password_generator(length: int, symbols: bool, uppercase: bool) -> str`**: Generates a password based on the specified parameters.

### ⚠️ Error Handling

The script includes error handling to ensure valid input. If the user enters an invalid password length (less than 1), a `ValueError` will be raised, providing feedback to the user.

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request. Whether it's fixing bugs, enhancing functionality, or adding features, your input is greatly appreciated.

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## 🙏 Acknowledgements

- Thanks to the **Python Software Foundation** for creating such a powerful programming language.
- The `secrets` module for providing a secure way to generate random passwords.

---

With this password generator, securing your online accounts has never been easier. **Generate strong, unique passwords effortlessly!**
