# wesng-wrapper
A bash wrapper script for bitsadmin's [wesng](https://github.com/bitsadmin/wesng).
This wrapper script provides the ability to filter out vulnerabilities without any exploits and to be able to filter by both the impact and severity of the exploit simultaneously.

```
Usage: wes [OPTION]... -f [systeminfo]
Search for possible Windows exploits given systeminfo.exe output

Windows Exploit Suggester 0.98 ( https://github.com/bitsadmin/wesng/ )

required arguments:
  -f    File        Specify the systeminfo file

optional arguments:
  -i    Impact      Only display vulnerabilities with a given impact
                    (Impacts: 'privilege', 'execution', 'denial', 'spoofing', 'disclosure', 'bypass')
  -s    Severity    Only display vulnerabilities with a given severity
                    (Severities: 'Moderate', 'Important', 'Critical')
  -x    Exploits    Only display vulnerabilities with exploits if passed
  ```
