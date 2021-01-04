# Machine Learning with Selenium and TensorFlow


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

This project is based on this repository <a href="https://github.com/adamleonsmith/seleniumMachineLearning">seleniumMachineLearning</a>

Train a Tensorflow model [based on Inception V3](https://cloud.google.com/tpu/docs/tutorials/inception) with custom set of images and apply the model to identify objects in a webpage with the help of selenium.

### Built With
* [TensorFlow](https://www.tensorflow.org/)
* [Docker](https://www.docker.com/)
* [Selenium](https://www.seleniumhq.org/)
* [And a bunch of python libraries](https://www.python.org/)



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is the list of things you need to have in your system.
1. Get [Docker Desktop](https://www.docker.com/products/docker-desktop) to pull Tensorflow images
2. Have [Python](https://www.python.org/downloads/) installed in the system

### Installation

1. Clone the repo
```sh
git clone https://github.com/dasxran/seleniumMachineLearning.git
```
2. Pull [Tensorflow image](https://hub.docker.com/r/dasxran/tensorflow) from Docker hub
```sh
docker pull dasxran/tensorflow:trainimages
```


<!-- USAGE EXAMPLES -->
## Usage

python3 tf_exec_identifySearchButton.py

Note that the chromedriver location will likely need to be changed, and the paths are linux style.


<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE` for more information.


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

Based on work by Ranjan Kumar Das
Project Link: [https://github.com/dasxran/seleniumMachineLearning](https://github.com/dasxran/seleniumMachineLearning)
