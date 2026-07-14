````markdown
# 🔎 Python Port Scanner

A simple TCP Port Scanner written in Python that scans one or multiple target IP addresses to identify open ports.

## 📌 Features

- Scan a single IP address
- Scan multiple IP addresses
- Detect open TCP ports
- Easy to understand and modify
- Lightweight and beginner-friendly

## 🛠️ Requirements

- Python 3.x
- termcolor

Install the required package:

```bash
pip install termcolor
```

## 📂 Project Structure

```
.
├── portscanner.py
└── README.md
```

## 🚀 Usage

Run the program:

```bash
python portscanner.py
```

Example:

```
[*] Enter Targets To Scan(split them by ,): 192.168.1.1
[*] Enter How Many Ports You Want To Scan: 100

Starting Scan For 192.168.1.1
[+] Port Opened 22
[+] Port Opened 80
```

Multiple targets:

```
[*] Enter Targets To Scan(split them by ,): 192.168.1.1,192.168.1.10
[*] Enter How Many Ports You Want To Scan: 1000
```

## ⚙️ How It Works

- Accepts one or more IP addresses from the user.
- Scans ports from **1** up to the specified maximum.
- Attempts a TCP connection to each port.
- Displays any port that accepts a connection.

## 📚 Technologies Used

- Python
- Socket Programming
- Termcolor

## ⚠️ Disclaimer

This project is intended **for educational purposes and authorized network testing only**. Only scan systems that you own or have explicit permission to test. Unauthorized scanning may violate laws or organizational policies.

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome. Feel free to fork the repository and submit a pull request.

Made with ❤️ using Python.
````

**Vivek Chouhan**

**INTERN ID-CITS5704**

This README is suitable for a beginner GitHub project and clearly explains what the project does and how to use it.
