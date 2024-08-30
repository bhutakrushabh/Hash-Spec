# Hash-Spec

**Hash-Spec** is a Python tool that helps identify the type of a hash based on its length and characteristics. It provides a quick way to determine the hashing algorithm used, along with the corresponding Hashcat mode for password cracking.

## Features

- Detects the likely hashing algorithm used based on the hash length.
- Provides the corresponding Hashcat mode, making it easier to use with password recovery tools.
- Supports various hash types including MD5, SHA1, SHA256, SHA512, and more.

## Installation

1. **Clone the Repository:**
```
git clone https://github.com/bhutakrushabh/hash-spec.git
cd hash-spec
```
2. **Install Required Packages:**
```
pip install termcolor
```
## Usage
To use Hash-Spec, run the script from the command line with the hash value you want to analyze.

```
python hash-spec.py <hash_value>
```
### Output:
```
Algorithm used: SHA1:100
```
This output indicates that the hash is most likely using the SHA1 algorithm with Hashcat mode 100.

## Help :
To display the help menu and usage instructions, run:
```
python hash-spec.py -h
```

## Contributing :
Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or submit an issue on the GitHub repository.

## Author
Created by Rushabh Bhutak
