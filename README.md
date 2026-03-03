# OSINT-Phone-number
Step-by-Step Installation in Kali Linux
1️⃣ Update Kali
sudo apt update && sudo apt upgrade -y
2️⃣ Install Required Packages
sudo apt install git python3 python3-venv python3-pip -y
3️⃣ Clone the GitHub Repository
git clone https://github.com/self72/OSINT-Phone-number.git


4️⃣ Go Inside the Tool Directory
cd 
5️⃣ Create Virtual Environment
python3 -m venv venv
6️⃣ Activate Virtual Environment
source venv/bin/activate


pip install phonenumbers
8️⃣ Run the Tool

Example:

python main.py -n +91 ..........

