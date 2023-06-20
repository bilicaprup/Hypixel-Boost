# Minecraft Proxy
## Features

前置
wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb
sudo apt-get update
sudo apt-get install -y dotnet-runtime-3.1


1. Custom motd
2. Modify client handshake packet

## How To Use

### 1. Install .NET 3.1

Windows: [Download .NET Core 3.1 Runtime (microsoft.com)](https://dotnet.microsoft.com/en-us/download/dotnet/3.1/runtime?cid=getdotnetcore)

Linux:

```shell
wget https://dot.net/v1/dotnet-install.sh -o dotnet-install.sh && chmod +x ./dotnet-install.sh && sudo ./dotnet-install.sh -c 3.1
```

### 2. Download the program and unzip it

Windows:

Go to [Releases](https://github.com/SkyAerope/MinecraftProxy/releases) and download, then unzip.

Linux:

````shell
wget https://github.com/SkyAerope/MinecraftProxy/releases/download/v1.0.0/release.zip
unzip release.zip
````

### 3. Start the program

```shell
dotnet ./MinecraftProxy2.dll
```

