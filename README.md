# ShadowSocksPac

A ShadowSocks Pac file Generator with fetched China IP range, which helps walk around GFW. It could Generate Pac file automaticlly base on your shadowsocks-gui config file.

中文介绍：[http://foryoung365.github.io/development/2015/02/15/shadowsockspac/](http://foryoung365.github.io/development/2015/02/15/shadowsockspac/).

## Usage

### Use Python script:

1. Install python from [https://www.python.org/](https://www.python.org/). If you have ShadowSocks-gui config file, jump to step 3;
2. Download latest ShadowSocks-gui from [ShadowSocks](http://sourceforge.net/projects/shadowsocksgui/files/dist/), version 2.3 or higher required. Or Simply run GenPac.py Without any argument, it will download a lastest one for you. Run ShadowSocks-gui and configure your server. Make sure it generate a config file.
3. Clone this project into your ShadowSocks-gui folder:

  git clone https://github.com/foryoung365/ShadowSocksPac.git

4.Copy the config file to the folder and run GenPac.py. Wait a few minutes while pac.txt generating:

  GenPac.py -f[FileName] -d[0 or 1]
  
  -f: your ShadowSocks-gui config file name, default:gui-config.json
  -d: 0-do not download 1-download latest ShadowSocks-gui automatically, default:1
  
5. Copy pac.txt to your ShadowSocks-gui folder. Open ShadowSocks-gui and select pac mode.
6. Have fun.

### Use executable file(Windows Only):
1. Download GenPac.rar from [here](http://foryoung365.github.io/attachments/GenPac.zip), decompress GenPac.exe to local disk. If you have ShadowSocks-gui config file, jump to step 3;
2. Download latest ShadowSocks-gui from [ShadowSocks](http://sourceforge.net/projects/shadowsocksgui/files/dist/), version 2.3 or higher required. Or Simply run GenPac.py Without any argument, it will download a lastest one for you. Run ShadowSocks-gui and configure your server. Make sure it generate a config file.
3. Copy GenPac.exe to your ShadowSocks-gui folder.
4. Run GenPac.exe and wait a few minutes while pac.txt generating.
5. Open ShadowSocks-gui and select pac mode.
6. Have fun.

