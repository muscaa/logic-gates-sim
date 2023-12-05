
# Logic Gates Simulator
[![Apache-2.0 License](https://img.shields.io/badge/License-Apache--2.0-blue.svg)](https://choosealicense.com/licenses/apache-2.0/)
## Quick Description

A Logic Gates Simulator made with the help of __LWJGL__ and __Slick2D__ in __Java 17__.

### Features

- All basic logic gates
- A save/load system
- Cross platform

### Planned Features

- Custom logic gates
- A logic calculator
## Running the program

If you don't have __Java 17__ already installed, you'll need it now. Here's the [link](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html).

After you have installed Java and added it to the __PATH__, you can download the application jar ([link](https://github.com/muscaa/logic-gates-sim/releases/tag/lgs)).

Now you place it where you want and create in that dir:

- on __windows__:

  a __run.bat__ file containing:

  ```bash
  start javaw -jar logic-gates-sim.jar
  ```

- on __linux/macos__:

  a __run.sh__ file containing:

  ```bash
  javaw -jar logic-gates-sim.jar
  ```

## Building from source

Clone this repo on your machine and build it with:

```bash
gradlew build
```
    
## Screenshots

![Screenshot](https://github.com/muscaa/logic-gates-sim/blob/main/images/screenshot.png?raw=true)