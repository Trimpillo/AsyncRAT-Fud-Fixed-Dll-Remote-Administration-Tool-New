# AsyncRAT
AsyncRAT stands as a Remote Access Tool (RAT) conceived for the purpose of distant supervision and command over remote computers through an encrypted connection ensuring security.

## How to Use

- Download the project to your computer as zip
- Extract Project to Folder.
- Make Sure You Have Visual Studio Installed on Your Computer
- [Click if Visual Studio is Not Installed](https://visualstudio.microsoft.com/en/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&passive=false&cid=2030)

### Compiling :
1. Open the solution file (.sln).
2. Select **Build Solution** from the **Build** menu or press `Ctrl+Shift+B` to compile the project.
3. When the build is complete, select **Start Without Debugging** from the **Debug** menu or press `Ctrl+F5` to run the project.

- The compiled files are inside the Binaries folder.


# Features
- Framework for dispatching and collecting directives through a plugin system
- Command center for client governance through a terminal interface
- Adaptable client manageable via Terminal commands
- Log server, meticulously recording all pivotal occurrences

## Encompassed Attributes:
- Viewer and recorder for client's screen
- Management of client's antivirus and system integrity
- Facilitated SFTP access for clients, including upload and download functionalities
- Interactive chat interface for both client and server
- Integration of Dynamic DNS and support for multiple servers (User-configurable)
- Mechanism for client password retrieval
- Incorporation of JIT (Just-In-Time) compilation within the client
- Incorporation of a client-side keylogger
- Adherence to anti-analysis protocols by the client (User-configurable)
- Orchestrated updates under server's control
- Activation of client antimalware during startup
- Editing of server configurations
- Multichannel reception on the server through customizable ports
- Rendering of server thumbnails
- Customized construction of server binaries (User-configurable)
- Implementation of server-side obfuscation (User-configurable)
- And a multitude of other functionalities!

### Technical Particulars
The subsequent online servers and resources find incorporation within this endeavor
* [pastebin.com] - employed for the "PasteBin" feature within the client builder
* [github.com] - employed for both downloading and uploading modifications to the project
### Setup & Implementation

The operation of AsyncRAT mandates the presence of the [.Net Framework](https://dotnet.microsoft.com/download/dotnet-framework/net46) v4 (client) and v4.6+ (server).

```diff
- To compile this project(s), utilize Visual Studio 2022
```

### Add-ons
At present, the application integrates several embedded DLLs (further elaboration below)

| Plugin | Origin |
| ------ | ------ |
| StealerLib | [gitlab.com/thoxy/stealerlib] |.

## LEGAL DISCLAIMER
##### I, as the creator, alongside all those engaged in the conception and realization of this application, hereby disclaim any culpability for consequences and/or destruction resulting from this software. You shoulder the complete onus for your deeds and concede that this software has been crafted solely for educational pursuits. Its intended use DOES NOT encompass malicious deployment or application on systems you lack ownership of or explicit authorization to operate and utilize this software on. By opting to employ this software, you inherently endorse the aforementioned stipulations.

## Licensing
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](/LICENSE)
The entitlement to this project adheres to the MIT License - refer to the [LICENSE](/LICENSE) file for comprehensive elucidation.