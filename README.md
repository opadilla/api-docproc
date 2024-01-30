# api-docproc

Document Processor API

ASP.NET Core API
Uses GdPicture.NET SDK for PDF manipulation capabilites provided by PDF related task types.

## Installing the .NET 8.0 SDK on Ubuntu

To develop and build .NET Core or .NET 8.0 applications on your local Ubuntu machine, you will need to install the .NET 8.0 SDK. The SDK provides you with the necessary tools to create, compile, and run .NET applications.

### 1. Register the Microsoft package repository

Open a terminal and run the following commands to register the Microsoft package repository:

```bash
wget https://packages.microsoft.com/config/ubuntu/22.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
```

Replace "22.04" with your Ubuntu version if necessary.

### 2. Update the package cache
Run the following command to update the package cache:
```bash
sudo apt-get update
```

### 3. Install the .NET 8.0 SDK
Once the package cache is updated, you can install the .NET 8.0 SDK with the following command:
```bash
sudo apt-get install -y dotnet-sdk-8.0
```

### 4. Verify the installation
After the installation is complete, you can verify that the .NET SDK is installed correctly by running:
```bash
dotnet --version
```
It should display the installed .NET SDK version (e.g., 8.0.x).

Once you've successfully installed the .NET 8.0 SDK, you can use it to create, build, and run .NET applications on your Ubuntu machine, including ASP.NET Core Web APIs.