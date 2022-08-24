## Deployment playbook goes here.
npm install
pm2 stop default
pm2 start npm -- start