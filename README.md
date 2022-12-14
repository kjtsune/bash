# Some script

## SSH Key Installer

Install SSH keys via GitHub, URL or local files

[Read the details in blog (in Chinese) | 中文教程](https://p3terx.com/archives/ssh-key-installer.html)

- Thanks

```
https://github.com/P3TERX/SSH_Key_Installer
```

- Usage

```
bash <(curl -fsSL github.com/kjtsune/bash/raw/main/ssh_key.sh) [options...] <arg>
```

- Example

```
bash <(curl -fsSL github.com/kjtsune/bash/raw/main/ssh_key.sh) -o -g kjtsune -p 2222 -d
```

- Options

* `-o` - Overwrite mode, this option is valid at the top
* `-g` - Get the public key from GitHub, the arguments is the GitHub ID
* `-u` - Get the public key from the URL, the arguments is the URL
* `-f` - Get the public key from the local file, the arguments is the local file path
* `-p` - Change SSH port, the arguments is port number
* `-d` - Disable password login

## Lisence

[MIT](https://github.com/P3TERX/SSH_Key_Installer/blob/master/LICENSE) © P3TERX
