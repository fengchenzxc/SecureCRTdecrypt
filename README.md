# SecureCRTdecrypt
SecureCRT批量解密工具 by fengchen

```
python3 securecrtdecryptV2.py -v 2 -p "" -f "/private/tmp/tmp" -s ini

optional arguments:
  -h, --help            show this help message and exit
  -v VERSION, --version VERSION
                        SecureCRT 7.x版本使用-v 1 ，8.x版本使用-v 2，默认为1
  -p CONFIGPASS, --configpass CONFIGPASS
                        v2中需要ConfigPassphrase，v1默认不需要
  -f FILE, --file FILE  Sessions文件夹，设置后会递归查询指定后缀的文件，windows中默认为
                        %APPDATA%\VanDyke\Config\Sessions\sessionname.ini
  -s SUFFIX, --suffix SUFFIX
                        指定后缀，默认为ini
```
