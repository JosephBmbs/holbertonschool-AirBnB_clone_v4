<div align="center">
  <h1>AirBnB Clone - Web Dynamic</h1>
  <img src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet.project.files/concepts/74/hbnb_step5.png" alt="AirBnB Clone path img">
</div>


## Table of Contents

- [Project Description](#project-description)
- [Team](#team)
- [Concepts](#concepts)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Troubleshooting](#troubleshooting)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Project Description

Welcome to the AirBnB Clone - Web Dynamic project! This project aims to replicate the functionality of Airbnb's website, focusing on the dynamic aspects. It is designed to be a collaborative effort, to be completed in teams of two people.

**Project Lead**: Guillaume, CTO at Holberton School

**Project Weight**: 2

**Project Review Date**: reviewed in the 1st Oct 2023.

**Manual QA Review**: Conducted by Firas Msekni and Youssef Saad, at 3:46 AM

### Concepts

For this project, you will be working with the following concepts:

- AirBnB clone
- Selector
- Get and set content
- Manipulate CSS classes
- Manipulate DOM elements
- Document ready
- Introduction to GET & POST requests
- HTTP access control (CORS)

### Learning Objectives

By the end of this project, you should be able to explain the following concepts without relying on external sources:

**General**

- How to make requests to your own API
- How to modify an HTML element's style
- How to get and update an HTML element's content
- How to manipulate the DOM
- How to make a GET request with JQuery Ajax
- How to make a POST request with JQuery Ajax
- How to listen/bind to DOM events
- How to listen/bind to user events

---

## Team

This project is to be completed in teams of 2 people. Collaborate effectively and create something amazing!

Firas Msekni: software engineering student

Youssef Saad: software engineering student

---

## Requirements

**General**

- Allowed editors: vi, vim, emacs
- All  files will be interpreted on Chrome (version 57.0)
- All  files should end with a new line
- A README.md file, at the root of the project folder, is mandatory
- The code should be semistandard compliant with the flag --global $: `semistandard *.js --global $`
- All JavaScript code must be in the `scripts` folder
- It must use JQuery version 3.x
- It are not allowed to use `var`
- HTML should not reload for each action: DOM manipulation, update values, fetch data…
- GitHub: There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.

### More Info

Before starting the project, ensure you have the following dependencies installed locally:

- `$ sudo apt-get install -y python3-lxml`
- `$ sudo pip3 install flask_cors` (if not already installed)
- `$ sudo pip3 install flasgger`

If you encounter issues with dependencies, consider these potential solutions:

- For a `jsonschema` exception: `$ sudo pip3 uninstall -y jsonschema` followed by `$ sudo pip3 install jsonschema==3.0.1`
- If you encounter a `No module named 'pathlib2'` error, install `pathlib2` with `$ sudo pip3 install pathlib2`

Ensure that ports are exposed in your Vagrantfile as needed:

```ruby
config.vm.network :forwarded_port, guest: 5001, host: 5001
```

Getting Started

To get started with this project, follow the installation instructions and guidelines below.

## Installation

Clone the project repository.
bash
Copy code
git clone https://github.com/your-username/airbnb-clone-web-dynamic.git
Install required dependencies:
bash
Copy code
sudo apt-get install -y python3-lxml
sudo pip3 install flask_cors
sudo pip3 install flasgger
Ensure you have JQuery version 3.x included in your HTML.
html
Copy code
<head>
    <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
</head>
You are now ready to start working on the project!
Troubleshooting

If you encounter any issues during the installation or while working on the project, refer to the troubleshooting section above for potential solutions. If the problem persists, seek assistance from your team members or the project lead.

## Usage

Provide instructions on how to use your project once it's set up. Include any important details, such as how to interact with the web application and any additional features or functionalities.

Contributing

If you would like to contribute to this project, please follow the standard guidelines for contributing to open-source projects. Create a pull request and ensure that your code adheres to the project's coding standards.

## License

This project is licensed under the MIT License.
