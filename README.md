Raven 

Raven is a Python-based CLI OSINT tool created for educational purposes. It combines username searches across popular platforms with basic IP information and networking utilities — all from a simple command-line interface.
Raven is an ongoing project created to improve my Python programming skills and learn more about HTTP requests, APIs, JSON, networking, and OSINT.
The project may look simple now, but I will keep learning and try to make it legendary. 

Features:
  Username Search

Search for a username across multiple popular platforms:

GitHub
Reddit
Steam
Twitch
X
YouTube
GitHub Search

Search for a GitHub username and retrieve publicly available information through the GitHub API.

Available information includes:

Name
Followers
Following
Public repositories
Location
Public email (if available)
IP Information

Raven can:

Detect your public IP address
Detect your local IP address
Search an IP address in the local IP database
Display country information
Display country code
Display ASN
Display organization
  
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
Username Search

Select:

[3] Search username

Enter a username and Raven will check the configured platforms.

GitHub Search

Select:

[1] GitHub

Enter a GitHub username or profile URL.

IP Information

Select:

[4] IP information

Available options:

[1] Find out your public IP
[2] Find IP address
[3] Find local IP
📁 Project Structure
Raven/
├── raven.py
├── ip_database.json
├── README.md
├── requirements.txt
└── CHANGELOG.md
🗺️ Roadmap
Current

Main menu

GitHub search

Username search

Reddit search

Steam search

Twitch search

X search

YouTube search

Public IP detection

Local IP detection

IP database lookup

Planned

VK search

Domain information

Search history

Reports

Better error handling

More username platforms

More IP information

Improved user interface

Raven v3.0

🧠 About the Project

Raven started as a small Python project for learning programming.

The first version was mainly focused on GitHub username searching. Since then, the project has grown into a small OSINT CLI tool with multiple modules.

Raven is continuously being developed and improved as I learn new Python concepts.

⚠️ Disclaimer

Raven is an educational project created for learning and experimentation.

Use this tool responsibly and only with information you are authorized to access.

Raven does not guarantee that information returned by third-party services is complete or accurate.

The author is not responsible for misuse of this software or for any damage caused directly or indirectly by its use.

👨‍💻 Developer

Created by holy_shit

Maybe Raven looks simple now, but I'll try to make it legendary. 🐦
