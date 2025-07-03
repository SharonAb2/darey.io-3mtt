# Git Version Control Basics

# PART 1: Github Setup and Configuration

This guide will help you through the basics of using the basics of Github, starting with the installation of Git, creating a repository, cloning it and pushing those changes back to Github.

## Install Git:

1. ### Download Git

* Visit the official website to download
* Click [Here](https://git-scm.com/downloads)
* Download the appropriate version for your operating system (Windows, macOS or Linux).

2. ### Install Git

* Follow the intallation instructions for your OS `operating system`
* Once installed, open a terminal or command prompt and verify the installation by running this command:
> git --version

* This would display the installed version of Git

![git --version](./img/1.%20git%20--version.png)

##  Github Account
### 1. Create a Github Account
* Click [Here](https://github.com/) to sign up

### 2. Login to Github

* Click here [Here](https://github.com/) to login using your details

![github signin](./img/2.%20Github%20signin.png)



# Create Github Repository

### 1. Create a new repository

* On Github click the "+" icon or "New" word in the top right corner and select "New Repository".

* Name the repository `Tom-Jerry`

*  Adding a description to the new repository is optional.

* Choose "Public" or "Private" visibility.
* Check the box to "initialize thisv repository with a README".
* Click "Create repository".


![Create new repo](./Img/3.%20Create%20new%20repo.png)



# Clone The Repository

### 1. Copy the repository URL

* On the github repository page, click the `code` button.

* Copy the HTTPS URL link e.g (https://github.com/your-username/tom-jerry.git) 

![Code and copy URL](./Img/4%20Code%20and%20copy%20URL.png)


### 2. Clone the repository locally

* Open your terminal or command prompt.

* Create a folder named **Git-Project**, using the commands below;

> mkdir Git-Project

* Then navigate into the `Git-Project`folder by running the command below

> cd Git-Project

* Clone the repository by using the copied URL

> git clone https://github.com/your-username/tom-jerry.git

* Navigate into the cloned repository

> cd tom-jerry

![cd Tom-jerry](./Img/5.%20cd%20Tom-jerry.png)

# Make Change and Commit

### 1. Create a new file:

* Create an empty `index.html` file by using the command below.

> touch index.html

* Add some content to the file by using a text editor or IDE.

### 2. Check Git Status

* Run the following command to see the changes that ha not been staged:



