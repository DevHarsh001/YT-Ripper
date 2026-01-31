# YT-Ripper

A minimalist, high-performance YouTube downloader for Windows. Built with Electron and powered by `yt-dlp` and `ffmpeg`, ensuring stable 1080p+ video downloads with perfectly merged audio.

<p align="center">
  <img src="https://i.ibb.co/TBQ7hvKv/image.png" width="600" title="Application Preview">
</p>

## Features

- **High Definition Support:** Downloads 1080p, 720p, and 480p video and high quality audio.
- **Portable:** Single executable file with zero installation required.
- **Privacy:** Your data remains on your computer.
- **Adfree:** Adfree software

## Download

Get the latest portable executable from the [Releases Page](https://github.com/DevHarsh001/YT-Ripper/releases).

---

## How to Use

<div align="center">

<h3>Step 1: Copy link of a YouTube video</h3>
<img src="https://i.ibb.co/RTxxcNxD/image.png" width="500">

<br><br>

<h3>Step 2: Open the tool</h3>
<img src="https://i.ibb.co/TBQ7hvKv/image.png" width="500">

<br><br>

<h3>Step 3: Paste the copied link</h3>
<img src="https://i.ibb.co/qMx8dZ5r/image.png" width="500">

<br><br>

<h3>Step 4: Select resolution</h3>
<img src="https://i.ibb.co/vC7NxByk/image.png" width="500">

<br><br>

<h3>Step 5: Check your downloads folder</h3>
<p>Your file will be ready immediately after the progress bar finishes.</p>

</div>

---

## Development Setup

If you want to build this app from source, follow these steps:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/DevHarsh001/YT-Ripper.git](https://github.com/DevHarsh001/YT-Ripper.git)
    cd YT-Ripper
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Setup FFmpeg**
    * Create a folder named `bin` in the project root.
    * Download **FFmpeg (Windows Build)** from [gyan.dev](https://www.gyan.dev/ffmpeg/builds/).
    * Extract `ffmpeg.exe` and place it inside the `bin/` folder.
    * *Check:* Your file path should be `YT-Ripper/bin/ffmpeg.exe`.

4.  **Run the App**
    ```bash
    npm start
    ```
    
## Maintenance

**Maintained by:** Harsh Tiwari **||**
**Email:** harshtiwari6060@gmail.com

Join Our [Discord](https://discord.gg/8EtrjWqgJe) to report bugs or to give suggestions
