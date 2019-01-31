# Task-1

### Made by David Carl
### www.dcarl.me

## Disclaimer

This is made on a unix based system and made for a unix based system, I cannot offer support for anything else. If you dont have a unix based system, I recommend you strongly to get one!

## Installation

### Local

I would do it this way to run it on you local computer.

```wget https://github.com/DavidCarl/Databases_Course/raw/master/Task-1/Task-1.zip```

use your favorite linux zip tool! I use the following

```unzip Task-1.zip```

See usage for how to use it!


### Docker

First download this script, I attached a command on 1 way to do it.

```wget https://github.com/DavidCarl/Databases_Course/raw/master/Task-1/docker_script.sh```

You should then run this command on it

```chmod 755 docker_script.sh```

now you can run the script like this

```./docker_script.sh```

This creates a file in your current directory called docker.db. It also runs my application through Docker so you dont need to install anything.

See usage for how to use it!

## Usage

You can see below how to use my program.

### Save to DB file
```python main.py save -k <key_value> -v <value_here>```

### Read from DB file
```python main.py read -k <key_value>```

### Help Commands
 ```python main.py --help```

 ```python main.py save --help```
 
 ```python main.py read --help```
