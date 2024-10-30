# Automated Time-Based SQL Injection Scanner
### Description
This Python script is an automated time-based SQL injection scanner designed to help identify SQL injection vulnerabilities in web applications. It uses time delays to detect if a target is vulnerable by checking the response time. With support for multi-threading and custom payloads, this tool scans multiple URLs at once, making it quick and efficient for large target lists.

### Features

1. Automated Scanning: Just provide a list of targets and payloads, and the script takes care of the rest.
2. Time-Based SQL Injection Detection: Uses time-based delays to check for SQLi vulnerabilities.
3. Multi-threading Support: Scan multiple targets simultaneously for faster results.
4.  Output Logging: Logs all vulnerable URLs into results.txt for easy reference.
5.  URL Encoding: Ensures payloads are URL-safe, reducing errors in requests.

### How It Works

The script appends SQL injection payloads to target URLs and checks the response time. If the response time exceeds a threshold (default: 10 seconds), it considers the target vulnerable and logs it.

### Requirements
1. need to be alive
2. need to have laptop or pc (phone that using termux is currently testing rn)
3. need a linux/termux terminal
4. python3
5. pip3
thats it i guess

### setup

```
git clone https://github.com/kryptonproject/TSQLI
.
cd TSQLI
.
pip3 install -r requirements.txt
.
python3 exploit.py

```

### Usage

```
make a target list contain a urls with params (example: https://target.com/news.php?id=1)
if you have your target list, run the script,
and it will ask you for target list and payload list,
enter your target list,
and the payload, you can use the one i currently use (you can use custom payload idc :D)
```

# screenshot

![Screenshot from 2024-10-30 22-05-15](https://github.com/user-attachments/assets/d8c2ca94-7b91-4a76-92f2-44e3203d0e68)
[Watch the demo video](https://cdn.videy.co/h5Ggp8bf1.mp4)


This tool is intended for educational and ethical hacking purposes only. Unauthorized use against systems without permission is illegal. The author assumes no responsibility for any misuse or damage caused by this tool.
License

This project is open-source and licensed under the MIT License.

Enjoy your scanning! 🎉
