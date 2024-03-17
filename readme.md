# SHA-1 Implementation in Python

This Python script implements the SHA-1 (Secure Hash Algorithm 1) hashing algorithm, which is used to generate a unique fixed-size hash value from input data. SHA-1 is no longer considered secure for cryptographic purposes due to vulnerabilities, but this script provides a basic implementation for educational purposes.

## Usage

To use the script, clone the repo, then run the sha1py.py from the command line with Python 3 and provide either a message or a file as input. The script will compute the SHA-1 hash of the input and print the result.

### Command Line Usage

```./sha1py.py <message or file>```
Replace `<message or file>` with the message you want to hash or the path to the file you want to hash.

## Examples

Compute the SHA-1 hash of a message:

Command: ```./sha1py.py hello```
Output: ```aaf4c61ddcc5e8a2dabede0f3b482cd9aea9434d   -   "hello"```


Command: ```./sha1py.py "Hello World!"```
Output: ```2ef7bde608ce5404e97d5f042f95f89f1c232871   -   "Hello World!"```

Command: ```./sha1py.py a.py```
Output: ```a579f2bb1c6a948e8e3e26391b0c92c8797ffa01   -   a.py```

## Requirements

- Python 3.x