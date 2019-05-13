# Python SSH Execution

Python library for executing local Python scripts on remote machines.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install python-ssh-exec
```

## Usage

```python
pyssh -f ~/path/to/script.py -h SERVER_ADDRESS -p PORT -u USERNAME -pw PASSWORD
```

_User_, _password_ and _port_ are optional fields. You can also set environment variables instead of including them:
`SSH_USER` and `SSH_PASSWORD`. `port` is defaulted to 22.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
