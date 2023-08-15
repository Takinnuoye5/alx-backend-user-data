# 0x01-Basic Authentication Project

This project is part of the ALX Africa program and follows the Holberton School curriculum. The goal of this project is to implement Basic Authentication in a back-end application. The project will be developed by Abiodun Adekunle.

## Table of Contents

- [Background Context](#background-context)
- [Resources](#resources)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Contributing](#contributing)
- [License](#license)

## Background Context

In this project, we will explore the authentication process and implement Basic Authentication for a simple API. While it's important to note that in real-world scenarios, you would use established modules or frameworks for authentication, this project will walk through each step of the Basic Authentication mechanism for learning purposes.

## Resources

Before starting the project, it's recommended to review the following resources:

- [REST API Authentication Mechanisms](https://www.youtube.com/watch?v=501dpx2IjGY)
- [Base64 in Python](https://docs.python.org/3/library/base64.html)
- [HTTP Header Authorization](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Authorization)
- [Flask](https://palletsprojects.com/p/flask/)
- [Base64 - concept](https://en.wikipedia.org/wiki/Base64)

## Learning Objectives

By the completion of this project, you should be able to:

- Explain the concept of authentication
- Understand what Base64 encoding is and how to use it
- Encode a string in Base64
- Describe the concept of Basic Authentication
- Send the Authorization header in HTTP requests

## Requirements

- Python Scripts: All code will be interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7.
- File Format: All files should end with a new line.
- Shebang Line: The first line of all files should be `#!/usr/bin/env python3`.
- README.md: A README file at the root of the project folder is mandatory.
- Coding Style: Your code should adhere to the `pycodestyle` style (version 2.5).
- Executability: All files must be executable.
- Documentation: All modules, classes, and functions should have appropriate documentation.
- Documentation Length: Documentations should be descriptive and explain the purpose of the module, class, or method.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Abiodun001-world/0x01-Basic_authentication.git
```

2. Navigate to the project directory:

```bash
cd 0x01-Basic_authentication
```

3. Set up a virtual environment (optional but recommended):

```bash
python3 -m venv venv
source venv/bin/activate
```

4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Start the development server:

```bash
flask run
```

2. Open a web browser and navigate to `http://127.0.0.1:5000/` to access the application.

3. Register a new user and log in with your credentials.

## Endpoints

The following endpoints are available:

- `POST /register`: Register a new user by providing a username and password.

- `POST /login`: Authenticate a user by providing their username and password.

- `GET /protected`: Access a protected route that requires authentication.

## Contributing

Contributions to this project are welcome! If you encounter any issues or would like to add new features, feel free to open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

