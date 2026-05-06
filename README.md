# 🔐 CipherX — Java Encryption Program

A substitution cipher encryption program built in Java, with a fully interactive web version deployed live.

🌐 **Live Demo:** [sohamsharmadev-svg.github.io/java-encryption](https://sohamsharmadev-svg.github.io/java-encryption/)

---

## 📌 About The Project

CipherX is a console-based Java application that encrypts and decrypts messages using a **substitution cipher**. Every printable ASCII character (32–126) is mapped to a randomly shuffled counterpart, making each key unique.

The project was later ported to a **web application** using HTML, CSS, and JavaScript — so anyone can use it directly in the browser without installing Java.

---

## ✨ Features

- 🔑 **Random Key Generation** — generates a new shuffled key every session
- ✏️ **Custom Key Support** — set your own key and share it with others
- 🔒 **Encrypt Messages** — converts plain text to cipher text
- 🔓 **Decrypt Messages** — reverses cipher text back to plain text
- 🌐 **Web Version** — fully functional browser app, no installation needed

---

## 🖥️ How It Works

The program maps all 95 printable ASCII characters to a randomly shuffled version of themselves:

```
Original:  !"#$%&'()*+,-./0123456789:;<=>?@ABC...
Encrypted: Xq2#mK9...  (shuffled randomly)
```

- **Encrypting** replaces each character with its shuffled counterpart
- **Decrypting** does the reverse lookup using the same key
- The same key must be used to decrypt a message that was encrypted with it

---

## 🚀 Getting Started (Java Console Version)

### Prerequisites
- Java 17 or higher installed
- Any terminal / command prompt

### Installation

```bash
# Clone the repository
git clone https://github.com/sohamsharmadev-svg/java-encryption.git

# Navigate into the project
cd java-encryption

# Compile the project
javac -d bin src\encryptionprogram\module-info.java src\encryptionprogram\EncryptionProgram.java src\encryptionprogram\Main.java

# Run the program
java --module-path bin -m encryptionprogram/encryptionprogram.Main
```

### Usage

Once running, use these keys to interact:

| Key | Action |
|-----|--------|
| `N` | Generate a new random key |
| `G` | Display the current key |
| `S` | Set a custom key |
| `E` | Encrypt a message |
| `D` | Decrypt a message |
| `Q` | Quit the program |

---

## 📁 Project Structure

```
java-encryption/
├── src/
│   └── encryptionprogram/
│       ├── Main.java               # Entry point
│       ├── EncryptionProgram.java  # Core logic
│       └── module-info.java        # Module declaration
├── bin/                            # Compiled .class files (auto-generated)
├── index.html                      # Web version
└── .gitignore
```

---

## 🌐 Web Version

The web version is built with vanilla HTML, CSS, and JavaScript — no frameworks or libraries needed. It replicates the full Java functionality in the browser:

- Generate random keys
- Set custom keys
- Encrypt and decrypt messages in real time
- Copy output with one click

**Live at:** [sohamsharmadev-svg.github.io/java-encryption](https://sohamsharmadev-svg.github.io/java-encryption/)

---

## 🛠️ Built With

- **Java 17** — core encryption logic
- **HTML5 / CSS3 / JavaScript** — web version
- **GitHub Pages** — free hosting for the web app

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Soham Sharma**
- GitHub: [@sohamsharmadev-svg](https://github.com/sohamsharmadev-svg)
