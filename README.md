# androfetch
 A pretty system information tool written in bash for termux on android.

![preview1](screenshots/s1.png)

**Note**: Use meslo nerd font.


### created by [Laraib07](https://github.com/laraib07)

## Table of contents
* [Installation](#installation)
* [Usage](#usage)
* [Custom logo](#custom-logo)
* [Screenshots](#more-screenshots)


## Installation

**Note**: Delete previous cache manually with 
```bash
rm -rf ~/.cache/androfetch/cache
```

1. Install fonts ( optional , else disable icons with `androfetch -i` )
```bash
wget https://raw.githubusercontent.com/laraib07/androfetch/main/font.ttf && mv font.ttf ~/.termux/
```

or

```bash
curl -O https://raw.githubusercontent.com/laraib07/androfetch/main/font.ttf && mv font.ttf ~/.termux/
```

2. Installing androfetch.
```bash
wget https://raw.githubusercontent.com/laraib07/androfetch/main/androfetch && chmod u+x androfetch && mv androfetch $PREFIX/bin/
```

or

```bash
curl -O https://raw.githubusercontent.com/laraib07/androfetch/main/androfetch && chmod u+x androfetch && mv androfetch $PREFIX/bin/
``` 

## Usage

Usage : **androfetch**  [-hci] [-n name|reset] [ -l filepath|reset]

option |   Description
:-----:|:---------------------------:
  -h   |     print this usage
  -c   |     build new cache
  -i   |     toggle icon visibility
  -n   |     set user name
  -l   |     set logo

## Custom logo

To set custom logo, save logo in a file without quoting or commenting
Add whitespaces to make every line equal in width.
Do not use broad logo which will cover significant space.
although you can use as many lines as you like like.

See sample_logo in this repo for reference.

After saving it use following command to set it.

```bash
androfetch -l <filepath>
```

## More Screenshots

![preview2](screenshots/s2.png)
![preview3](screenshots/s3.png)
![preview4](screenshots/s4.png)

