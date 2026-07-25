# Evil_FPF (v1.0) ☠️

![Evil_FPF Banner](evil2.jpg)

Evil_FPF is an Advanced Facebook Phishing Framework Tool specifically tailored for Termux and Kali Linux systems. No root permissions are required to operate this framework.

> [!WARNING]
> **Educational & Testing Purposes Only**
> This tool is strictly developed for authorized penetration testing, cyber security research, and educational demonstrations. The author accepts absolutely no liability and holds no responsibility for any misuse or damage caused by this software.

---

## 🐧 1. Installation on Kali Linux

Run these commands one by one in your terminal:

```bash
sudo apt update && sudo apt upgrade -y
```

```bash
sudo apt install git python3 python3-pip -y
```

```bash
git clone https://github.com/alphinux/Evil_FPF-v1.0-.git
```

```bash
cd Evil_FPF
```

```bash
pip3 install flask
```
```bash
chmod +x *
```

```bash
python3 evilfp.py
```

---

## 📱 2. Installation on Termux (No Root Required)

Run these commands one by one inside your Termux application:

```bash
pkg update && pkg upgrade -y
```

```bash
pkg install git python -y
```

```bash
git clone https://github.com/alphinux/Evil_FPF-v1.0-.git
```

```bash
cd Evil_FPF
```

```bash
pip install flask
```

```bash
chmod +x *
```

```bash
python3 evilfp.py
```

---

## 🛠️ Features
* **No Root Needed**: Runs seamlessly out of the box on standard Android/Termux setups.
* **Dual OS Support**: Works natively on both Debian-based Kali distributions and Android shells.
* **Lightweight Setup**: Built using Flask for minimized network and processing footprint.
