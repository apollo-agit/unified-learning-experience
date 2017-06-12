# unified-learning-experience
Polymer application for the Unified Learning Experience


## Prerequisites
Node must be installed:
[Download Node](https://nodejs.org/en/download/)

From Node we must init the install of...
* NPM (Node Package Manager)
* Bower package manager
* Polymer Command Line Tool
```
npm install npm -g
npm install bower -g
npm install polymer-cli -g
```

## How to Build

The process uses the polymer based tooling for testing and building

```
git clone https://github.com/apollo-agit/unified-learning-experience.git
cd unified-learning-experience
npm install
bower install
polymer lint
polymer test
polymer build
```

## How to Run

We now need to start a local dev middleware server in the command instance

```
polymer serve
```

Open a browser and navigate to
http://localhost:8081/