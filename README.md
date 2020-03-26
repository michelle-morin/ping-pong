# _Ping Pong_

#### By _**Michelle Morin**_

## Description

_This webpage accepts input of a number, and returns a list of numbers from 1 to the user input number. For each number in the list, numbers divisible by 15 are replaced with "ping-pong", numbers divisible by 5 are replaced with "pong" and numbers divisible by 3 are replaced by "ping-pong"._

## Specifications:

| Specification | Example Input | Example Output |
| ------------- |:-------------:| -------------------:|
| Webpage returns list of numbers from 1 to user input number | 5 | 1, 2, 3, 4, 5 |
| Webpage replaces all numbers evenly divisible by 3 with "ping" | 3 | 1, 2, "ping" |
| Webpage replaces all numbers evenly divisible by 5 with "pong" | 5 | 1, 2, "ping", 4, "pong" |
| Webpage replaces all numbers evenly divisible by 15 with "ping-pong" | 5 | 1, 2, "ping", 4, "pong", "ping", 7, 8, "ping", "pong", 11, 12, 13, 14, "ping-pong" |

## Setup/Installation Requirements

### Node install

#### For macOS:
_If Homebrew is not installed on your computer already, then install Homebrew by entering the following two commands in Terminal:_
* ``$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"``
* ``$ echo 'export PATH=/usr/local/bin:$PATH' >> ~/.bash_profile``

_Install Git with the following command:_
* ``$ brew install git``

_Next, install Node.js by entering the following command in Terminal:_
* ``$ brew install node``

#### For Windows:
_Please visit the [Node.js website](https://nodejs.org/en/download/) for installation instructions._

### Setup/install this application

_Clone this repository via Terminal using the following commands:_
* ``$ cd desktop``
* ``$ git clone https://github.com/michelle-morin/ping-pong``
* ``$ cd ping-pong``

_Confirm that you have navigated to the ping-pong project directory (e.g., by entering the command_ ``pwd`` _in Terminal).

_Next, install node package manager (npm) at the project's root directory via the following command:_
* ``$ npm install``

_Open this application via live server using the following command:_
* ``$ npm run start``

_To view/edit the source code of this application, open the contents of the doctor directory in a text editor or IDE of your choice (e.g., to open all contents of the directory in Visual Studio Code on macOS, enter the command_ ``code .`` _in Terminal)._

## Technologies Used
* _Git_
* _HTML_
* _CSS_
* _JavaScript_ 
* _jQuery_ 
* _npm_ 
* _Webpack_ 

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Michelle Morin_**
