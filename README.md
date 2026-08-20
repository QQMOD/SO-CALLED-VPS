# Pro VPS Panel (Railway Deployable)

A lightweight web-based VPS panel that runs on Railway. Each user can upload, run, and manage Python/Node/Shell files with real-time logs.

## Owner Credentials
- Username: `MR SHUVO`
- Password: `admin123`

## Deploy on Railway

1. Push this project to a GitHub repository
2. Go to Railway → New Project → Deploy from GitHub
3. Railway automatically detects `nixpacks.toml` and deploys
4. Generate a domain in Railway settings
5. Login with owner credentials

## Features

**Owner (MR SHUVO):**
- Create user accounts (username, password, expiry hours)
- Auto-login links for each user
- Extend or delete user accounts
- Automatic account expiry with process cleanup

**Users:**
- Upload multiple files (up to 200MB)
- Run `.py`, `.js`, `.sh` files
- Start/Stop/Restart processes
- Real-time logs streaming
- Install modules: `pip install` or `npm install`
- View and delete files

## Environment Variables

- `SECRET_KEY` - Set this for persistent sessions (optional)

## Local Development

```bash
pip install -r requirements.txt
python app.py
# Open http://localhost:5000
