# NetMapGeo

**NetMapGeo** is a network visualization project that captures and analyzes network packets. It leverages Wireshark for packet capture, processes the data into CSV format, and generates KML files for visualization on platforms like Google Earth. This project is useful for network analysis, monitoring, and educational purposes.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Captures network packets and extracts relevant data.
- Converts packet data into CSV format for analysis.
- Generates KML files for geographical visualization of network traffic.
- Simple and intuitive command-line interface.

## Installation

Clone the repository:

```bash
git clone https://github.com/Srijan-Jalal/NetMapGeo.git
cd NetMapGeo
```

## Usage
Use Wireshark for capturing your packets and saved it as `wire.pcap` Make sure to have files in the same directory and Also generate you ipinfo.io API token key

Run the packet analysis script:

The script will generate `network_data.csv` and `network_lines.kml` files in the project directory.

Upload the generated KML file to Google Earth for 3D visualization of network traffic flows.

## Technologies Used

- Python - Core programming language.
- Pandas - Data manipulation and analysis library.
- Matplotlib - Library for data visualization.
- SimpleKML - Library for creating KML files.
- Scapy - Packet manipulation tool for network analysis.
- Requests - HTTP library for making API calls.

## Project Structure

```
NetMapGeo/
├── Main.ipynb            # Main Jupyter Notebook for packet processing
├── wire.pcap             # Sample packet capture file
├── network_data.csv      # Output CSV file containing packet data
├── network_lines.kml     # Output KML file for visualization
└── README.md             # Project documentation
```

## Contributing

Feel free to fork this repository, create a new branch, and submit pull requests. All contributions are welcome to improve NetMapGeo!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Wireshark - For capturing network traffic.
ipinfo.io - For IP geolocation.

---
