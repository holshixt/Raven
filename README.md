Raven 

Raven is a Python-based CLI OSINT tool created for educational purposes. It combines username searches across popular platforms with basic IP information and networking utilities — all from a simple command-line interface.
Raven is an ongoing project created to improve my Python programming skills and learn more about HTTP requests, APIs, JSON, networking, and OSINT.
  
  Installation
1. Install Python

Make sure Python 3 is installed on your system.

2. Clone the repository
git clone https://github.com/holy/Raven.git

cd Raven
3. Install dependencies
pip install -r requirements.txt

After extraction, the project structure should look like:

Raven/
├── raven.py
├── ip_database.json
├── README.md
├── requirements.txt
└── CHANGELOG.md
5. Run Raven
python raven.py
  Usage

After starting Raven, the main menu will appear:

[1] GitHub
[2] VK (In development)
[3] Search username
[4] IP information
[0] Exit

