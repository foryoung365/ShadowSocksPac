# ShadowSocksPac

A ShadowSocks Pac file Generator. Generate Pac file automaticlly base on your shadowsocks-gui config file.

## Usage

### Use Python script:

1. Install python from [https://www.python.org/](https://www.python.org/).
2. Download newest ShadowSocks-gui from [ShadowSocks](http://sourceforge.net/projects/shadowsocksgui/files/dist/), version 2.3 or higher required. Run ShadowSocks-gui and configure your server. Make sure it generate a config file.
3. Clone this project into your ShadowSocks-gui folder:

  git clone https://github.com/foryoung365/ShadowSocksPac.git

4. Run GenPac.py and wait a few seconds while pac.txt generating:

    GenPac.py -c[ConfigFileName]
  
5. Copy pac.txt to your ShadowSocks-gui folder. Open ShadowSocks-gui and select pac mode.
6. Done.

### Use executable file:
1. Download newest ShadowSocks-gui from [ShadowSocks](http://sourceforge.net/projects/shadowsocksgui/files/dist/), version 2.3 or higher required. Run ShadowSocks-gui and configure your server. Make sure it generate a config file.
2. Copy GenPac.exe to your ShadowSocks-gui folder.
3. Run GenPac.exe and wait a few seconds while pac.txt generating.
4. Open ShadowSocks-gui and select pac mode.
5. Done.

