# Port-_Scanner

This is a Python script for a basic port scanner that allows you to scan a range of ports on a target host. It can be useful for network administrators and security professionals to identify open ports on a remote system. 

## Usage

To use this port scanner, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Shantanu-100/Port-_Scanner/port-scanner.git
   ```

2. Navigate to the project directory:

   ```bash
   cd port-scanner
   ```

3. Run the script with Python 3, providing the target host and the range of ports you want to scan:

   ```bash
   python3 port_scanner.py TARGET START_PORT END_PORT
   ```

   Replace `TARGET` with the IP address or hostname of the target you want to scan, `START_PORT` with the starting port number, and `END_PORT` with the ending port number.

## Example

Here's an example of how to use the port scanner:

```bash
python3 port_scanner.py example.com 80 100
```

This will scan ports 80 to 100 on the host "example.com" and report which ports are open.

## Features

- Multi-threaded scanning: The script utilizes threads to scan multiple ports simultaneously, which can significantly speed up the scanning process.
- Timeout: The script sets a timeout of 2 seconds for each port scan. If a connection cannot be established within this time, the port is considered closed.

## Important Notes

- Ensure you have the necessary permissions to run this script, especially when scanning ports below 1024.
- Port scanning without proper authorization may be illegal or unethical. Use this script only on systems you have explicit permission to scan.
- This script is a basic example and may not be suitable for all use cases. More advanced port scanning tools and techniques exist for comprehensive network assessment.

## Acknowledgments

- This script is a simple demonstration and may not cover all edge cases.
- Be responsible and ethical when using this script. Respect the laws and regulations governing network security and scanning in your jurisdiction.
- Inspired by [Python](https://www.python.org/) and [Socket Programming](https://docs.python.org/3/library/socket.html).

Please feel free to contribute, report issues, or suggest improvements to this project.
