

## 🥇 Step-by-Step Installation in Kali Linux

### 1️⃣ Update Kali

```bash
sudo apt update && sudo apt upgrade -y
```

---

### 2️⃣ Install Required Packages

```bash
sudo apt install git python3 python3-venv python3-pip -y
```

---

### 3️⃣ Clone the GitHub Repository



```bash
git clone https://github.com/sundowndev/PhoneInfoga.git
```

---

### 4️⃣ Go Inside the Tool Directory

```bash
cd toolname
```

---

### 5️⃣ Create Virtual Environment

```bash
python3 -m venv venv
```

---

### 6️⃣ Activate Virtual Environment

```bash
source venv/bin/activate
```

You’ll see:

```
(venv) kali@kali:~/toolname$
```

---

### 7️⃣ Install Dependencies

If repo has `requirements.txt`:

```bash
pip install -r requirements.txt
```

If not:

```bash
pip install .
```

---

### 8️⃣ Run the Tool

Example:

```bash
python3 main.py
```

or

```bash
python3 tool.py -h
```

---

# ⚡ Method 2 — Using pipx (BEST for Security Tools)

If it’s a Python CLI tool, `pipx` is even better.

### Install pipx

```bash
sudo apt install pipx -y
pipx ensurepath
```

Restart terminal.

### Install tool

```bash
pipx install toolname
```

OR directly from GitHub:

```bash
pipx install git+https://github.com/username/toolname.git
```

---

# 🧠 Pro Hacker Setup (Recommended Structure)

Create a tools folder:

```bash
mkdir ~/tools
cd ~/tools
```

Clone everything there.

---

# 💡 If You Get Error Again

If you see:

```
externally-managed-environment
```

It means you forgot to activate venv.

Run:

```bash
source venv/bin/activate
```

---

If you tell me:

👉 Which GitHub tool name
👉 What exact error you're getting

I’ll give you exact fix for that tool step-by-step 😎

