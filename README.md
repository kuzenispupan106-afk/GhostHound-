# GhostHound-
An OSINT Tool
# GhostHound v1.0
An Open Source Intelligence (OSINT) & Defensive Security Recon Toolkit. Developed by Celestial Brothers.

## Installation & Deployment

To clone and deploy this tool directly onto your NetHunter or Termux environment, run the following commands:

```bash
# Clone the repository from GitHub
git clone [https://github.com/kuzenispupan106-afk/GhostHound-.git](https://github.com/kuzenispupan106-afk/GhostHound-.git)

# Move into the project directory
cd GhostHound-

# Install the required framework dependencies
pip install python-dotenv rich requests colorama phonenumbers python-whois dnspython beautifulsoup4 aiohttp validators --break-system-packages
python3 ghosthound.py
