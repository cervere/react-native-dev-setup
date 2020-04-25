# Setting up dev environment to start learning react-native (Ubuntu)

As in the react-native [documentation](https://reactnative.dev/docs/environment-setup), to get started with developing simple apps using react-native, two things are assumed to be installed.
 - Node.js
 - An Android Emulator (At the moment, iOS is not the priority)

So first, to install `node.js`, we need to install `nvm` (Node Version Manager). 

Depending on whether `curl` or `wget` is used :
```
~$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
OR
```
~$ wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
Note that the terminal needs to be closed and reopened to start accessing `nvm` command
```
~$ nvm --version
0.34.0
```
Now install the latest (stable) version of nodejs :
```
~$ nvm install --lts
```
OR
```
~$ nvm install node
```
