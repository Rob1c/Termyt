
# Termyt©

![Termyt is Easy!](usr/share/pixmaps/logo-whtbkg.png)

Termyt is a CLI tool for downloading audio and videos from streaming sites like YouTube, yt-dlp based 
 
Protected by CC-BY-NC License 4.0 (see License at bottom)

Note: the README.md files in the auto-generated source codes .zip and .tar.gz are wrong, but everything else is correct. Hope Github fixes this!

## Installation
## Linux

You can start Termyt immediately by executing the main code, after unpacking the tarball: 

```bash
  tar -xvzf termyt_<VERSION>.tar.gz
  cd termyt/usr/bin
  chmod +x termyt
  ./termyt
  
```
## Debian-based systems

On debian-based systems, you can download the .deb package and consequently be able to run Termyt anywhere, even having the icon (.desktop file). 
```bash
  sudo apt install ./termyt_<VERSION>.deb
```
Note: "./" before the .deb package, indicates to apt that the package you want to install is local (your PC), and not from a repository!
## Windows
For executing Termyt in Windows, you require two simple dependencies:
1. yt-dlp, which is included in the Termyt folder (for updating yt-dlp, simply download the latest .exe from the [yt-dlp page](https://github.com/yt-dlp/yt-dlp))
2. Git for Windows, which consents you to execute Shell Scripts (.sh) which are UNIX/Linux native. 
\
Once you installed Git for Windows, extract the .zip file, access termyt/usr/bin , ensure that "termyt" is executable by checking the relative checkbox in the file's properties, and you're ready to go!

## How to Uninstall
## Linux ad Windows

To uninstall Termyt on Linux and Windows (you won't need it!), simply delete the main folder where you ran the program.

## Debian-based systems
If you installed Termyt on Debian-based systems using the .deb package, simply reverse the installation process:

```bash
sudo apt remove termyt
```
## Authors

- [@Robic](https://www.github.com/Rob1c)


## Contributing

Contributions are always welcome!

If you have any suggestions for improvements, please let me know here: 
roberto.chichiarelli@gmail.com. 

## License

                                                            
CC-BY-NC License v4.0 

Termyt (c)
                                                                                                    
Copyright (c) 2026 Roberto Chichiarelli "Robic"
Created by Roberto Chichiarelli
GitHub: https://github.com/Rob1c
Development period: July 2025 –

Any violation of these terms may result in termination of rights granted under this license.
                                                                                                  
For commercial licensing inquiries, contact: roberto.chichiarelli@gmail.com

## Troubleshooting

### Issue 1.0
Since the program is so simple today, fortunately there is only one known common problem. It manifests itself as follows (or similar, given the continuous updating of yt-dlp):
```bash
ERROR: fragment 1 not found, unable to continue [download]
Got error: HTTP Error 403: Forbidden
[same error in loop...until the download starts or the program stops]
```
### Solution to Issue 1.0
#### This error indicates that yt-dlp is not updated, so follow the update guide at the Installation section for your OS.
## Support

For support, feel free to email! roberto.chichiarelli@gmail.com 


![Enjoy Termyt!](usr/share/pixmaps/logo-whtbkg.png)

