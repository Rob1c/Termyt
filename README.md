
# Termyt©

Termyt is a CLI tool for downloading audio and videos from streaming sites like YouTube, yt-dlp based 
 
Protected by Robic License 1.0 (see License at bottom)


## Installation
## Linux

You can start Termyt immediately by executing the main code, after unpacking the tarball: 

```bash
  tar -xvzf termyt-v<version>.tar.gz
  cd termyt/opt/termyt
  chmod +x termyt
  ./termyt
  
```
## Debian-based systems

On debian-based systems, you can download the .deb package and consequently be able to run Termyt anywhere, even having the icon (.desktop file). 
```bash
  sudo apt install ./termyt-v<version>.deb
```
Note: "./" before the .deb package, indicates to apt that the package you want to install is local (your PC), and not from a repository!
## Windows
For executing Termyt in Windows, you require two simple dependencies:
1. yt-dlp, which is included in the Termyt folder (for updating yt-dlp, simply download the latest .exe from the [yt-dlp page](https://github.com/yt-dlp/yt-dlp))
2. Git for Windows, which consents you to execute Shell Scripts (.sh) which are UNIX/Linux native. 
\
Once you installed Git for Windows, extract the .zip file, access termyt/opt/termyt , ensure that "termyt" is executable by checking the relative checkbox in the file's properties, and you're ready to go!

## How to Uninstall
## Linux ad Windows
Have you ever seen these two together? Well, this is one of Termyt's many magical features!

To uninstall Termyt on Linux and Windows (you won't need it!), simply delete the main folder where you ran the program.

## Debian-based systems
To uninstall Termyt on Debian-based systems, simply reverse the installation process:

```bash
sudo apt remove ./termyt-v<version>.deb 
```
## Authors

- [@Robic](https://www.github.com/Rob1c)


## Contributing

Contributions are always welcome!

If you have any suggestions for improvements, please let me know here: 
roberto.chichiarelli@gmail.com. 

## License

Robic Public License v1.0

Copyright (c) 2025 Roberto Chichiarelli 

"Robic" Created by Roberto Chichiarelli 

GitHub: https://github.com/Rob1c

Development period: July – September 2025

Permission is hereby granted to any person to use, copy, modify, and distribute this software and its source code for personal, educational, or non-commercial purposes, provided that:

The original author is credited in all copies and derivative works.

The source code must remain accessible and included with any distribution.

Commercial use — including but not limited to selling, monetizing via ads, donations, or bundling with paid services — is strictly prohibited for anyone other than the author.

The original author retains full rights to monetize, license, or relicense this software.

This software is provided "as is", without warranty of any kind.

Any violation of these terms may result in termination of rights granted under this license.

## Troubleshooting

### Issue 1.0
Since the program is so simple today, fortunately there is only one known common problem. It manifests itself as follows:
```bash
ERROR: fragment 1 not found, unable to continue [download]
Got error: HTTP Error 403: Forbidden
[same error in loop...until the download starts or the program stops]
```
### Solution to Issue 1.0
#### This error indicates that yt-dlp is not updated, so follow the update guide at the Installation section for your OS.
## Support

For support, feel free to email! roberto.chichiarelli@gmail.com 


![Enjoy Termyt!](/assets/icons/logo.png)

