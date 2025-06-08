# FT_IRC

## ⚡ Core Features

- Handles multiple client connections using sockets and poll
- Implements core IRC commands (JOIN, PART, PRIVMSG, NICK, MODE, KICK, INVITE, TOPIC, etc.)
- Supports channel management, user privileges, and operator commands
- Robust parsing of client messages and server responses
- Error handling and compliance with IRC RFC standards

## Compilation Instructions
To compile and run this program:
```sh
git clone https://github.com/Tudor-Ursescu/FT_IRC.git
cd FT_IRC
```
Compile everything:
```sh
make
```
And in order to run it:
```sh
./ircserv <port> <password>
```
- '<port>' : Port number to listen on
- '<password>' : Server password for client authentication

## Usage

1. Build and run the server as shown above.
2. Connect with an IRC client(e.g. irssi) using the chosen port and password.

## Contributors

- [**Tudor Ursescu**](https://github.com/Tudor-Ursescu)
- [**Hryhorii Zakharchenko**](https://github.com/grysha11)
- [**Tudor Lupu**](https://github.com/DRACULATudor)