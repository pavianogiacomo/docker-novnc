# docker-novnc

A basic Dockerfile with noVNC and a GUI for Alpine.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## About
This repository provides a lightweight Docker image built on Alpine Linux with a graphical user interface accessible via noVNC. It is designed to provide a simple and efficient way to run GUI-based applications inside a Docker container, accessible through your web browser.

## Features
- Lightweight Alpine-based Docker image.
- Browser-based GUI access using noVNC.
- Easy-to-configure and deploy.

## Getting Started

### Prerequisites
To use this repository, you need:
- Docker installed on your machine. You can download it from [Docker's official website](https://www.docker.com/).
- A web browser to access the GUI (e.g., Chrome, Firefox).

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/pavianogiacomo/docker-novnc.git
   cd docker-novnc
   ```
2. Build the Docker image:
   ```bash
   docker build -t docker-novnc .
   ```

### Usage
1. Run the Docker container:
   ```bash
   docker run -p 6080:6080 docker-novnc
   ```
2. Open your web browser and go to `http://localhost:6080`. You will see the GUI interface powered by noVNC.

---

## Contributing
Contributions are welcome! If you find a bug or have a feature request, please open an issue. If you want to contribute code, fork the repository and submit a pull request.

### Steps to Contribute:
1. Fork this repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a brief description of your changes"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
