# Machine Learning Project Setup

This guide will help you set up a **Python virtual environment** (`venv`) and install the required dependencies for this Machine Learning project.

## 📌 Prerequisites

- **Python 3.10+** installed (Check with `python --version`)
- **pip** installed (Check with `pip --version`)

---

## 🚀 Setting Up the Virtual Environment

### **1️⃣ Navigate to Your Project Folder**

Open a terminal (**PowerShell** or **Command Prompt**) and go to your project directory:

```sh
cd /path/to/your/project
```

### **2️⃣ Create a Virtual Environment (`venv`)**

```sh
python -m venv venv
```

This will create a `venv/` folder inside your project.

### **3️⃣ Activate the Virtual Environment**

#### **🔹 Windows (PowerShell)**

```sh
venv\Scripts\Activate
```

#### **🔹 Windows (Command Prompt - cmd)**

```sh
venv\Scripts\activate.bat
```

#### **🔹 macOS/Linux**

```sh
source venv/bin/activate
```

After activation, your terminal will show `(venv)`, indicating you are inside the virtual environment.

### **4️⃣ Upgrade `pip`**

```sh
python -m pip install --upgrade pip
```

---

## 📦 Installing Required Libraries

Instead of manually installing each library, install all dependencies from `requirements.txt`:

```sh
pip install -r requirements.txt
```

If `requirements.txt` is not available, you can manually install common ML libraries with:

```sh
pip install numpy pandas scikit-learn matplotlib seaborn jupyter notebook tensorflow torch torchvision xgboost lightgbm opencv-python
```

---

## ❌ Deactivating the Virtual Environment

When you're done working, deactivate the virtual environment:

```sh
deactivate
```

---

## 🎯 Summary of Commands

```sh
# Navigate to project folder
cd /path/to/your/project

# Create virtual environment
python -m venv venv

# Activate virtual environment
venv\Scripts\Activate  # PowerShell
venv\Scripts\activate.bat  # CMD

# Upgrade pip
python -m pip install --upgrade pip

# Install dependencies from requirements.txt
pip install -r requirements.txt

# Deactivate virtual environment
deactivate
```

---

Now your virtual environment is fully set up! 🚀 Happy coding! 😊


