# Offensive Umbraco: XSS Weaponisation

- Title
- Whoami
- What is Umbraco?
- What is XSS?
- Demo 1

- Objective
- Cookie Stealer
- HttpOnly
- HttpOnly Workarounds
- Create User Payload
- Demo 2a

- Backoffice Accessed - What Next?
- Remote Code Execution with Razor
- Web Shell Code
- Demo 2b

- Issues with Approach
- OpSec Fails/Improvements
  - Raw JS - obfuscate
  - Inline JS - host externally
  - User account created/logged into
    - Skip entirely, update template from payload
  - Web shell dropped to disk
  - Command passed in query string - encode in header instead
  - Others
    - New process spawned by web server worker process
- Objective
- New Razor Payload
- New JavaScript Payload
- Web Delivery with Metasploit
- Creating a Metasploit Module
- Demo 3

- Defences
- XSS Prevention
- CSP
- Principle of Least Privilege
- Folder Permissions

- Summary
