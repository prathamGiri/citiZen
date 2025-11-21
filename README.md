# Deployment SOP

## Steps
1. Pull the latest code  
2. Build the project  
3. Restart the service

## Commands

```bash
git pull origin main
npm install
npm run build
sudo systemctl restart my-app
