# vna
VNA setup

## miniVNA Tiny

http://miniradiosolutions.com/54-2/

### Tools

http://vnaj.dl2sba.com/

#### Setup

```sh
sudo usermod -a -G tty yourname
sudo usermod -a -G dialout yourname
```

#### Run

```
java -Dsun.java2d.uiScale=2 -jar vnaJ.3.1.22.jar
```
