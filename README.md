# SharpUserIP

## Feature Overview

- Server login logs (requires administrator privileges)
- Retrieve login logs from domain controllers or remotely to quickly obtain IP addresses associated with domain users


## Instructions for Use

```
  ___ _                  _   _            ___ ___
 / __| |_  __ _ _ _ _ __| | | |___ ___ _ |_ _| _ \
 \__ \ ' \/ _` | '_| '_ \ |_| (_-</ -_) '_| ||  _/
 |___/_||_\__,_|_| | .__/\___//__/\___|_||___|_|
                   |_|


Get the log of successful login or the specified user


  -H             Specify the machine IP or machine name
  -U             Administrator account name
  -P             Administrator account password
  -D             Specify the time range (days) for enumeration
  -F             Enumerate specified users
  -O             Path to save the result, by default save to the log.txt of the current path
  -All           Get logs from all domain controllers

  Usage:
       SharpUserIP.exe -d 7
       SharpUserIP.exe -h ip -d 7
       SharpUserIP.exe -h ip -d 7 -f user1,user2
       SharpUserIP.exe -h ip -u username -p password -d 7
       SharpUserIP.exe -h ip -u username -p password -d 7 -all
       SharpUserIP.exe -h ip -u username -p password -d 7 -f user -o C:\path\result.txt
```

Server Log Retrieval:

<img width="1252" height="550" alt="Working-Group" src="https://github.com/user-attachments/assets/b2964fd4-c5cf-4ed9-a665-f2a372526812" />

Remote Log Retrieval Within Domain:

<img width="1016" height="454" alt="domain" src="https://github.com/user-attachments/assets/b64eb434-aa2b-4259-ab60-9cb3871418e9" />

## Disclaimer

This tool is intended solely for **legally authorized** enterprise security development activities. If you need to test the tool's functionality, please set up your own target machine environment.

When using this tool, you must ensure that such actions comply with local laws and regulations and that you have obtained sufficient authorization. **Do not scan unauthorized targets.**

Should you engage in any illegal activities while using this tool, you shall bear full responsibility for the consequences. The author shall not be held liable for any legal or related responsibilities.

Before installing and using this tool, please **carefully read and fully understand all terms and conditions**. Restrictions, disclaimers, or other provisions affecting your significant rights may be highlighted for your attention through bold text, underlining, or similar formatting. Unless you have thoroughly read, fully understood, and accepted all terms of this agreement, please refrain from installing and using this tool. Your use of the tool or any other express or implied indication of acceptance of this agreement shall be deemed as your acknowledgment that you have read and agreed to be bound by this agreement.

## Update Log

- Supports .NET Framework 4.0 and 5.0
