# GhostHound-
An OSINT Tool

## Installation & Deployment

To clone and run this tool safely in an isolated environment, execute the following commands:

```bash
# Clone the repository from GitHub
git clone [https://github.com/kuzenispupan106-afk/GhostHound-.git](https://github.com/kuzenispupan106-afk/GhostHound-.git)

# Move into the project directory
cd GhostHound-

# Create a virtual environment named 'venv'
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate

# Install all the required framework dependencies safely
pip install python-dotenv rich requests colorama phonenumbers python-whois dnspython beautifulsoup4 aiohttp validators

# Make the tool executable
chmod +x GhostHound

# Execute the tool
./GhostHound
