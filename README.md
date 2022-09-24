# Intro to Git/GitHub

## What is Git?
Git is a distributed version control system [1], keeping track of file changes and enabling collaboration with others.

[1] https://git-scm.com/

### What is GitHub?
GitHub is a company. It allows you to freely store your code in the cloud and **uses git** to keep track of file changes. In addition, it has many more tools to help you collaborate and share your code with others. It is widely used by both companies and inviduals to store code and share code/collaborate with others.

## Installation and Setup
There are many ways to install git.

### Windows
Download the [installer](https://gitforwindows.org/) and follow installation steps: https://gitforwindows.org/

### Mac
Homebrew - Homebrew is a very useful tool that manages and installs packages on macOS or linux
* Install Homebrew: https://brew.sh/
  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
* Install Git
  ```bash
  brew install git
  ```

### Linux
(Use your package manager)
  ```
  apt-get install git

  yarn install git

  dnf install git
  ```
