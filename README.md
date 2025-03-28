# Peer-to-Peer File Sharing System

## Overview
This project is a simple Peer-to-Peer (P2P) File Sharing System implemented in Python using sockets. It allows users to send and receive files directly between peers without the need for a central server.

## Features
- Peer-to-peer file transfer.
- Supports multiple concurrent connections.
- Secure and efficient file handling.
- Simple command-line interface.

## Prerequisites
Ensure you have the following installed:
- Python 3.x

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/p2p-file-sharing.git
   ```
2. Navigate to the project folder:
   ```bash
   cd p2p-file-sharing
   ```
3. Ensure Python is installed:
   ```bash
   python --version
   ```

## Usage
### Starting as a Server (Receiver)
1. Run the following command:
   ```bash
   python p2p_file_sharing.py
   ```
2. Select `server` mode when prompted.
3. The server will start listening for incoming file transfers.

### Starting as a Client (Sender)
1. Run the script:
   ```bash
   python p2p_file_sharing.py
   ```
2. Select `client` mode when prompted.
3. Enter the target peer's IP address and port number.
4. Provide the filename you want to send.
5. The file will be transmitted to the target peer.

## Example Usage
- Server: `python p2p_file_sharing.py` → Choose `server`
- Client: `python p2p_file_sharing.py` → Choose `client`, enter IP & port, select file

## Notes
- Ensure both peers are on the same network or that necessary firewall rules are configured for communication.
- This implementation is for educational purposes; consider adding encryption for secure file transfers.

## License
This project is licensed under the MIT License.

## Author
- [Your Name]
- GitHub: [Your GitHub Profile](https://github.com/your-username)

