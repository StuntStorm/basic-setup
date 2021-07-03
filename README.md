  # StuntStorm's Easy to use **Basic Setup NPM**

Basic Setup commands for discord bot. A Few commands created for a youtube video

![@stuntstormmath (3)](https://user-images.githubusercontent.com/56226566/124359639-7348c300-dc43-11eb-9ff2-126cb4bf98b3.png)



## Installation ⚒️

### ``` npm i @stuntstorm/basic-setup --save```

## Usage

### Require with any Variable
```
const package = require("@stuntstorm/basic-setup")
```

### Featured Commands 🐱‍🏍

#### PING COMMAND : 
#### Use this to check the Ping Rate

```
package.ping(message);
```
#### TICKET COMMAND : 
#### Use this to create private ticket with staff members (any user can access this command)

```
package.ticket(message)
```
#### BAN LIST COMMAND : 
#### Use this command to view all the Banned Users from your server

```
package.banlist(message)
```
#### EMOJI LIST COMMAND : 
#### Use this command to view all the Emojis from your server

```
package.emojilist(message)
```
#### RECORDING COMMAND : 
#### Use this command to push the chat upwards and make avoid messages being recorded

```
package.recording(message)
```

## Setup 🛠️

#### Setting Up Ping Command
```
const package = require("@stuntstorm/basic-setup")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!ping") {
    package.ping(message);
  }
});

client.login("token");
```
#### Setting Up Ticket Command
```
const package = require("@stuntstorm/basic-setup")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!ticket") {
    package.ticket(message);
  }
});

client.login("token");
```
#### Setting Up Ban List Command
```
const package = require("@stuntstorm/basic-setup")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!banlist") {
    package.banlist(message);
  }
});

client.login("token");
```
#### Setting Up Emoji List Command
```
const package = require("@stuntstorm/basic-setup")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!opban") {
    package.emojilist(message);
  }
});

client.login("token");
```
#### Setting Up Recording Command
```
const package = require("@stuntstorm/basic-setup")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!recording") {
    package.recording(message);
  }
});

client.login("token");
```
## Example Scenerio 💻

#### Index.js Code : 
![image](https://user-images.githubusercontent.com/56226566/124360067-57deb780-dc45-11eb-8318-68d46e86a593.png)
#### Discord Output : 
![image](https://user-images.githubusercontent.com/56226566/124360578-46e37580-dc48-11eb-801d-52f10abfb62c.png)



## Support 🐱‍💻

Feel free to join the support server : https://discord.gg/u6XzUFkKTn

StuntStorm's Github : https://github.com/StuntStorm

More NPM Packages : https://www.npmjs.com/~stuntstorm

## Bots using this Project 👾
### [StuntStorm Discord bot](https://discord.com/oauth2/authorize?client_id=850011982777417759&scope=bot&permissions=268443702) by StuntStorm#7231

## NOTE 🗃️

This package is protected under MIT license. 🔒


### Created and Published by StuntStorm
