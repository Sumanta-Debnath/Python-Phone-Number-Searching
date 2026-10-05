# Python Phone Number Searching

This project is a simple Python script that looks up information about a phone number using the `phonenumbers` library. Given a phone number defined in [test.py](test.py), the script in [main.py](main.py) parses the number and prints its approximate geographic location along with the name of the carrier or service provider associated with it. It relies on the `geocoder` and `carrier` modules from the `phonenumbers` package to perform these lookups, making it a handy starting point for anyone wanting to explore basic phone number validation and metadata extraction in Python.

## Requirements

- Python 3
- `phonenumbers` library (install with `pip install phonenumbers`)

## Usage

Update the phone number in [test.py](test.py), then run the script:

```bash
python main.py
```
