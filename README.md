# Port Scanner

A simple Python-based port scanner that checks for open ports on a given target IP address or hostname.

---

## Features
- Scans ports in the range **50 to 2000**.
- Displays open ports on the target machine.
- Shows the start time of the scan.
- Handles common exceptions such as:
  - Invalid arguments
  - Hostname resolution errors
  - Connection errors
  - Keyboard interrupts

---

## Requirements
- Python 3.x
- Internet connection (for scanning remote hosts)

---

## Usage
```bash
python3 scanner.py <ip_or_hostname>
```

### Example
```bash
python3 scanner.py 192.168.1.1
```

---

## Output
```
--------------------------------------------------
Scanning target 192.168.1.1
Time started : 2025-11-25 10:17:06
--------------------------------------------------
Port 80 is open
Port 443 is open
...
```

---

## Notes
- The default timeout for each port check is **1 second**.
- Scanning ports without permission may be illegal. Use this tool responsibly and only on systems you own or have explicit permission to scan.

---

## License
This project is licensed under the MIT License.
