# Lua

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This repository contains a collection of Lua programs and scripts.

## Table of Contents
- [What is Lua](#what-is-lua)   
- [Installation](#installation)
  - [Installing Lua](#installing-lua)    
    - [Windows](#windows)
    - [Linux](#linux)
    - [macOS](#macOS)  
  - [Installing Repository](#installing-repository)  
- [Usage](#usage)
  - [Running Lua Programs](#running-lua-programs)
  - [Using LuaRocks](#using-luarocks)
- [Contributing](#contributing)
- [License](#license)

## What is Lua

Lua is a lightweight, high-level scripting language that is often used as an embedded language in other applications. It was created in the mid-1990s by Roberto Ierusalimschy, Waldemar Celes, and Luiz Henrique de Figueiredo, and is known for its simplicity, efficiency, and extensibility.

Lua is designed to be easily embedded into other programs, and it is commonly used in applications such as video games, embedded systems, and scripting for other languages like C and Python. Lua has a simple and intuitive syntax, with support for procedural, object-oriented, and functional programming paradigms.

Lua is dynamically typed, meaning that the types of variables and expressions are determined at runtime, and it has a garbage collector that automatically manages memory, making it easy to write efficient code. Lua also has a powerful and flexible metatable system, which allows for metaprogramming and custom behavior for objects.

## Installation

### Installing Lua

These are the general steps to install Lua on different platforms. However, the exact steps may vary depending on the specific operating system and version you are using. It's always a good idea to refer to the official documentation for your platform to get more detailed installation instructions.

#### Windows

1. Download the Lua installation executable from the official Lua website.
2. Run the downloaded file and follow the installation instructions.
3. Once the installation is complete, you can use any text editor or IDE (Integrated Development Environment) to write and run Lua code.

#### Linux

1. Install Lua using the package manager for your Linux distribution. For example, on Ubuntu, you can use the following command:

```
sudo apt-get install lua5.1
```

2. Once Lua is installed, you can use any text editor or IDE to write and run Lua code.

#### macOS

1. You can use a package manager like Homebrew to install Lua. Open a terminal and run the following command:

```
brew install lua
```

2. Once Lua is installed, you can use any text editor or IDE to write and run Lua code.

Alternatively, you can also download the Lua installation package for macOS from the official Lua website and follow the installation instructions.

### Installing Repository

You can download individual files, copy & paste code, or clone the repository

```
git clone https://github.com/Eggy115/Lua.git
```

      
## Usage

### Running Lua Programs

1. Clone the repository. If you have written your own programs, save the program with a `.lua` file extension.
2. Open a terminal or command prompt and navigate to the directory where the Lua program is saved.
3. Run the following command to run the Lua program:

```
lua <filename.lua>
```

For example, if you have a Lua program named `hello.lua`, you can run it using the command:

```
lua hello.lua
```

This will execute the Lua program and display the output, if any, in the terminal or command prompt.

### Using LuaRocks

LuaRocks is a package manager for Lua that allows you to easily install and manage Lua modules. You can use it to add functionality to your Lua programs by installing third-party libraries.

1. Install LuaRocks by following the installation instructions provided on the official LuaRocks website.
2. Once LuaRocks is installed, you can use it to install Lua modules. For example, to install a module named my_module, you can run the following command:

```
luarocks install my_module
```

3. After installing a Lua module, you can use it in your Lua programs by requiring it in your code. For example, to use the my_module module in your hello.lua program, you can add the following line at the beginning of your Lua code:

```lua
require("my_module")
```

This will make the functions and variables defined in the `my_module` module available for use in your program.

## Contributing

Contributions are always welcome! Follow these steps to contribute:

1. Fork the repository and make your changes. 
2. Submit a pull request with your changes.
3. Create an issue if you find a bug or have a feature request.

Please make sure to adhere to the [code of conduct](CODE_OF_CONDUCT.md) and the [contributing guidelines](CONTRIBUTING.md).

## License

This repository is licensed under the [GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.html). See the [LICENSE](LICENSE) file for more information.
