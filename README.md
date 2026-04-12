# Host `smcwebos.ipk` on Render (Static Site)

## 1) Create a GitHub repo
Upload the contents of this folder to a new GitHub repository.

## 2) Create Render Static Site
- Render Dashboard -> New -> Static Site
- Connect your repo
- Build Command: (leave empty)
- Publish Directory: public

Deploy.

## 3) Your IPK URL
After deploy, the IPK will be available at:
https://YOUR-SERVICE.onrender.com/smcwebos.ipk

## 4) Install on LG professional screens (no Developer Mode)
On many LG webOS Signage displays you can install via:
- EZ Settings -> SI Server Setting
- Application Launch Mode: Local
- Application Type: IPK
- Local Application Upgrade: REMOTE
- Set the URL to the IPK URL above, then reboot if required by the menu.

## 5) Update process
When you publish a new build, replace `public/smcwebos.ipk` and redeploy.
