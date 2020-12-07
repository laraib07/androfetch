# androfetch
 A pretty system information tool written in bash for termux on android.

![preview1](screenshots/s1.png)

**Note**: Use meslo nerd font.
 

### created by [Laraib07](https://github.com/laraib07)

## Installation
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

Usage : **androfetch**  [-hci] [-n name]

option |   Description
:-----:|:---------------------------:
  -h   |     print this usage
  -c   |     build new cache
  -i   |     toggle icon visibility
  -n   |     set user name

## More Screenshots

![preview2](screenshots/s2.png)
![preview3](screenshots/s3.png)
![preview4](screenshots/s4.png)
