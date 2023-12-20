Docker-app-Zenity
Streamline your Docker image management and deployment process with this user-friendly shell script using Zenity dialogs. This script simplifies Docker login, allows easy input of Docker image names, facilitates Dockerfile selection, and enables image push to your personal Docker account.

Prerequisites
Make sure you have Docker installed on your system before using this script. You can download and install Docker from the official Docker website.

Installing Zenity
Follow the instructions below to install Zenity on your system based on your operating system:

For Ubuntu/Debian:

sudo apt-get update
sudo apt-get install zenity

For Fedora:

sudo dnf install zenity

For CentOS:

sudo yum install zenity

For Arch Linux:

sudo pacman -S zenity

For macOS:

If you don't have Homebrew installed, install it first:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Then, install Zenity:
brew install zenity

Usage
Clone this repository to your local machine:


git clone https://github.com/Amolkadwe/Docker-app-Zenity.git
cd docker-app-zenity
Make the script executable:

chmod +x docker-app.sh
Run the script:

bash
Copy code
./docker-app.sh

Follow the on-screen instructions to perform Docker login, input Docker image names, select Dockerfile, and push the image to your Docker account.
