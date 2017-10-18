# RitaloBot ![Alt text](https://travis-ci.org/blackdev1l/ritalobot.svg?branch=master)

Telegram bot written in Golang which uses Markov Chain stored in Redis

Installation
------------
You need *golang* >= *1.3* and *redis* installed on your machine.  
`go get github.com/blackdev1l/ritalobot`

Usage
------------

#### Flags
```
flag | default | help
-c="./config.yml": path for ritalobot config
-conn="tcp": type of connection and/or ip of redis database
-p=6379: port number of redis database
-token="": authentication token for the telegram bot
```

#### Config file
Create a `config.yml` or rename `example.yml` editing the variables.  
Make sure to have redis-server started.

TODO
------------

- [x] Flags
- [x] Yaml config
- [ ] Increase / decrease chance from command
- [ ] Better Markov chain
- [ ] Command to start or stop bot


![Works on my machine](http://www.edsquared.com/content/binary/Windows-Live-Writer/dbb6c39a79dc_68DE/WorksOnMyMachine_3.png)
