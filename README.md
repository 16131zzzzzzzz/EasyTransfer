<div align="center">
<img src="client/public/favicon.svg" alt="logo" width="100" height="100" />

<h1>EasyTransfer</h1>

Share simply & stay anonymous

[简体中文](README_ZH-cn.md) | English

[![GitHub issues](https://img.shields.io/github/issues/WCY-dt/EasyTransfer)](https://github.com/WCY-dt/EasyTransfer/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/WCY-dt/EasyTransfer)](https://github.com/WCY-dt/EasyTransfer/pulls) [![GitHub license](https://img.shields.io/github/license/WCY-dt/EasyTransfer)](https://github.com/WCY-dt/EasyTransfer/blob/main/LICENSE) ![GitHub package.json version](https://img.shields.io/github/package-json/v/WCY-dt/EasyTransfer?filename=client%2Fpackage.json)

<strong style="font-size: 24px;">👉 EXPERIENCE NOW: <a href="https://file.ch3nyang.top/">EasyTransfer</a></strong>

</div>

![Sample](./example.png)

EasyTransfer is a free, anonymous, encrypted, and easy-to-use E2EE file transfer tool. You only need to visit a simple web page to connect to **any device** in **any network** using a device code.

It is built using webRTC and Vue.js, and there is

- **NO** need to install any software
- **NO** need to register an account
- **NO** need to scan QR codes
- **NO** need to share URL links
- **NO** need to upload files to the server[^1]
- **NO** need to worry about the network environment

## How to use

1. Visit [EasyTransfer](https://file.ch3nyang.top/) on the two devices where you need to transfer files.
2. Enter the four-digit device code of any device into the device code input box of the other device and click the connect button.
3. After waiting for the connection to succeed, you can drag and drop the file to the file area on the web page, or click the file area to select the file. Supports sending multiple files at once.
4. In the settings, you can customize the STUN server and TURN server, or specify the maximum number of connections.

## Notes

- This project is hosted on a free server. Please do not abuse it.

## Self-deployment

Please refer to the [project Wiki](https://github.com/WCY-dt/EasyTransfer/wiki/Navigator).

## Acknowledgements

- Thanks to [metered](https://www.metered.ca/) for providing free STUN and TURN servers.
- Thanks to [glitch](https://glitch.com/) for providing free signaling servers.

[^1]: If the communicating peers need to penetrate the intranet, the file may be uploaded to the free TURN server provided by this project. You can avoid this by deploying a trusted TURN server yourself.

## Statistics

> Thanks to [Ruanyifeng](http://www.ruanyifeng.com/blog/2024/12/weekly-issue-329.html) for the recommendation!

[<img src="https://starchart.cc/WCY-dt/EasyTransfer.svg?axis=%23343a40&line=%23007bff" alt="Stargazers over time" style="zoom: 67%;" />](https://starchart.cc/WCY-dt/EasyTransfer)
