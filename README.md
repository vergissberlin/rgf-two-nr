# Node-RED regenfass
================

Deploy Node-RED for regenfass on Railway.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/IaInHw?referralCode=h8bD3s)

## ✨ Features

- Node-RED accessible on HTTPS
- Password Authentication (Set username & password in environment variables)
- Persistent PostgreSQL database for flows, settings and more

## 🐍 How to Deploy

1. Click Deploy on Railway
2. Wait for Build & Deployment to Finish
3. Refresh the Web Server x2 (See notes below)
4. Login with credentials (**Username:** battle & **Password:** snake)

## 📝 Notes

- Railway server currently requires 2x refreshes to successfully seed the database due to a 🐛 (PRs for fixes welcome 🙏)

## Acknowledgements

The code used in this repository is based on incredible work from developers in the Node-RED Community and beyond including:

### Node-RED Starter Code

- IBM - https://github.com/IBM/node-red-app
- Atsushi Kojo - https://github.com/joeartsea/node-red-heroku
- Sam Machin - https://github.com/sammachin/node-red-heroku

### regenfass Flow Code

- André Lademann - https://flows.nodered.org/flow/6cbf34b31e1890bb7a638005bcc4f54b

### Advanced regenfass Logic
- @mkaleung - https://github.com/mkaleung/regenfass
- @hatben - https://github.com/hatben/todd
