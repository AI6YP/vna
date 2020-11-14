## miniVNA

Tiny VNA setup

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

## Nano VNA 2

### NanoVNA-QT

```bash
sudo zypper in fftw3-devel libQt5Charts5-devel libQt5Charts5 libQt5Svg5 libqt5-qtsvg-devel

mkdir nanovna
cd nanovna/
git clone git@github.com:nanovna/NanoVNA-QT.git
cd NanoVNA-QT/
autoreconf --install
./configure
make

qmake-qt5
make


cd libxavna/xavna_mock_ui/
qmake-qt5
make
...
cd vna_qt/
qmake-qt5
make

../run ./vna_qt

```
