# Oticon Audio Explorers 2018 (Software Challenge)
## TeamName';DROP TABLE Teams;--
### Authors: 
_Thomas Nilsson (s144470@student.dtu.dk)_
_Simon Christensen (s163951@student.dtu.dk)_

## How to run the project

#### Setup Peripheal Device Emulation
Install Bleno
`sudo npm install bleno`

Clone the repo
`git clone https://github.com/thomasnilsson/OticonBluetooth`

Go to the script folder
`cd OticonBluetooth/bleno/examples/echo`

Install all messing dependencies, only works with python 2.7
`sudo npm install --python=python2.7`

Run the script
`node main.js`

#### Install iOS App
Open the `OticonBTLE` Project in Xcode

Deploy the application to a physical iOS device  

(This will not work with an iOS emulator since you are already using the laptop as peripheal device)

