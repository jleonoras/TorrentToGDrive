# Torrent to Google Drive Downloader 🚀

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/0xc3nt4ur10n/TorrentToGDrive/blob/main/TorrentToGDrive.ipynb)

A powerful and easy-to-use torrent downloader that runs directly in a Google Colab notebook. Download files from magnet links or `.torrent` files and save them directly to your Google Drive.

---

## ⚠️ Important: Google Colab Policies

It's important to understand that using this tool for torrenting **may violate Google Colab's Terms of Service and Acceptable Use Policy**.

* **Prohibited Uses**: Google's policies often prohibit peer-to-peer file-sharing. Running a torrent client falls into this category.
* **Resource Limits**: Colab environments are not intended for long-running, high-bandwidth processes. Continuous seeding or downloading large files can lead to your session being terminated.
* **Illegal Activity**: Downloading copyrighted material without permission is illegal and strictly against Google's terms.

**Use at Your Own Risk.** You are solely responsible for your activity on Google Colab. Misuse can lead to being temporarily or permanently blocked from the service. This tool is provided for educational and experimental purposes only.

---

## Features ✨

* **Google Drive Integration**: Mounts your Google Drive to save downloads directly to the cloud.
* **Organized Folders**: Automatically sorts your downloads into categories like Movies, TV Shows, Music, and more.
* **Multiple Input Methods**: Supports both magnet links and `.torrent` file uploads.
* **Live Progress Monitoring**: A dynamic dashboard shows real-time download/upload speeds, progress, ETA, and seeding status.
* **User-Friendly Interface**: Simple command-line prompts guide you through the process.

---

## How to Use 📝

1.  **Open in Colab**: Click the "Open in Colab" button at the top of this repository.
2.  **Run the Steps**: Execute the cells in the notebook in order:
    * **Step 1: Install libtorrent and Initialize Session**: This sets up the necessary torrenting engine.
    * **Step 2: Mount Google Drive**: Authorize Colab to access your Google Drive. This is where your files will be saved.
    * **Step 3: Add From Magnet Link or Torrent File**: Follow the prompts to enter a magnet link or upload a `.torrent` file and select a save location. You can add multiple torrents.
    * **Step 4: Download File**: This cell starts the download process and displays the live progress dashboard.

---

## Donations 💖

If you find this tool helpful and would like to support its development, please consider making a donation. Your support helps keep the project alive and allows for future improvements!

[![Donate with PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/jleonoras)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/jleonoras)

Thank you for your support!

---

## Developer Note

This project was developed with the assistance of AI tools. I provided the core logic and structure, and the AI helped generate the boilerplate code.

---

## License 📄

This project is licensed under the MIT License - see the `LICENSE` file for details.
