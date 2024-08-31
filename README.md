# NoNet

NoNet is a Python-based application for offline communication and file sharing between systems using the `socket` library. It allows users to establish connections and exchange messages and files without requiring an internet connection.

## Features

- **Offline Communication:** Establish direct communication between systems without internet access.
- **File Sharing:** Share files between connected devices using a simple interface.
- **Real-Time Messaging:** Send and receive messages in real-time over the local network.
- **Simple Setup:** Minimal configuration required to get started.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/M-Aadhi/NoNet.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd NoNet
   ```
3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   
   1.Start the server:
   ```bash
   python server.py
   ```
   2.Start the client:
   ```bash
   python client.py
   ```

Ensure that both server and client scripts are configured to connect to each other. You may need to modify the IP addresses and ports if running on different systems.

## Usage

1. **Server:**

   - Launch the server script on the main system.
   - The server will start listening for incoming connections from clients.

2. **Client:**

   - Launch the client script on other systems.
   - The client will connect to the server and allow for communication and file sharing.

3. **Send and Receive Files:**

   - Use the provided functions in the client to send files to the server.
   - The server will handle receiving and saving files.

4. **Send and Receive Messages:**

   - Send messages from the client, which will be displayed by the server and other connected clients.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
