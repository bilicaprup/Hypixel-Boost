# Minecraft Proxy
## Features

前置

wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb

sudo dpkg -i packages-microsoft-prod.deb

rm packages-microsoft-prod.deb

sudo apt-get update

sudo apt-get install -y dotnet-runtime-3.1

Linux:

wget https://github.com/SkyAerope/MinecraftProxy/releases/download/v1.0.0/release.zip
unzip release.zip

dotnet ./MinecraftProxy2.dll

