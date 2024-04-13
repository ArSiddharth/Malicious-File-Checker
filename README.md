# Malicious-File-Checker :lady_beetle:
A command-line tool for analyzing the security status of files using the API. This tool generates the hash of the provided file and submits it for analysis after it gives a detailed report on any potential threats detected.

## Features

- **File Security Analysis**: Quickly analyze the security status of any file by submitting its hash to HA.
- **Detailed Reports**: Receive detailed reports from HA regarding any threats detected in the file.
- **Easy-to-Use Command-Line Interface**: Simple and intuitive command-line interface for easy interaction.

## Prerequisites

- Python 3.x installed on your system.
- A valid HA API key.

## Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/ArSiddharth/Malicious-File-Checker.git
```

2. Navigate to the project directory:

```
cd Malicious-File-Checker
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage
Run the script from the command line and provide the path to the file you want to analyze along with your HA API key:


> python Malicious_file_checker.py /path/to/your/file api_key


Replace /path/to/your/file with the path to the file you want to analyze and your_ha_api_key with your actual HA API key.

## Example
```
python Malicious_file_checker.py sample_file.exe abcdef1234567890
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

1. Fork it (<https://github.com/ArSiddharth/Malicious-File-Checker/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
   
Support
For any inquiries or support, please contact [@Siddharth](https://github.com/ArSiddharth/Malicious-File-Checker).
