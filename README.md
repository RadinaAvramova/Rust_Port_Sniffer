# Rust Port Sniffer
Welcome to the Rust Port Sniffer project! This Rust application provides a simple port scanning tool that allows users to discover open ports on a target host. With the Rust Port Sniffer, users can perform network reconnaissance to identify potential vulnerabilities or services running on remote systems.

## Features
1. **Port Scanning:** Implements port scanning functionality to check for open ports on a target host within a specified range.

2. **Multi-threaded:** Utilizes multi-threading to perform concurrent port scans, improving scanning speed and efficiency.

3. **Customizable Options:** Allows users to customize scanning parameters such as the target host, port range, and timeout settings.

4. **TCP Protocol:** Utilizes the TCP protocol for port scanning, sending SYN packets to determine port status.

5. **Output Formatting:** Formats and displays scan results in a user-friendly manner, indicating open and closed ports.

## Installation
To run the Rust Port Sniffer, follow these steps:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/Rust_Port_Sniffer.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd Rust_Port_Sniffer

3. **Build the Application:** Build the Rust binary for the port sniffer using Cargo, the Rust package manager:

cargo build --release

## Usage
1. **Start the Port Sniffer:** Run the built binary to start the port sniffer:
   
cargo run --release -- <target_host> <start_port> <end_port>

Replace <target_host> with the IP address or hostname of the target host, <start_port> with the starting port number, and <end_port> with the ending port number of the port range to scan.

2. **View Scan Results:** After the port scanning process completes, the application will display the results, indicating open and closed ports on the target host.

## Customization
1. **Port Range:** Customize the range of ports to scan by adjusting the <start_port> and <end_port> parameters.

2. **Timeout Settings:** Adjust timeout settings for network requests to balance scan speed and accuracy.

3. **Output Formatting:** Modify output formatting options to customize the display of scan results according to your preferences.
