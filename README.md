# vna
miniVNA Tiny VNA setup

### Setup OpenSuse

```sh
echo "$USER"

# setup groups
sudo usermod -a -G tty,dialout <yourname>

cd programs
# download the program
wget http://download.dl2sba.com/vnaj/3.2.7/vnaJ.3.2.7.jar

# run the program
java -Dsun.java2d.uiScale=2 -jar vnaJ.3.2.7.jar
```

### Other Links

  * http://miniradiosolutions.com/54-2/
  * http://vnaj.dl2sba.com/
  * https://github.com/tx0/minivna/
  * http://wiki.oz9aec.net/index.php/MiniVNA_ICD
  * https://github.com/Hamlib/Hamlib/tree/master/miniVNA
  * https://github.com/drandrewthomas/vnamini_sharp
