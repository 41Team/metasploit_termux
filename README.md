# Metasploit Framework in Termux

![Metasploit 6 running](https://github.com/41Team/metasploit_termux/blob/master/screenshot.png)

### Manual
```bash
pkg install unstable-repo

pkg install wget

pkg install ruby

gem install bundler

wget https://raw.githubusercontent.com/gushmazuko/metasploit_in_termux/master/metasploit.sh

chmod +x metasploit.sh

./metasploit.sh
```
## After installation complete
Start `postgresql`
```bash
./postgresql_ctl.sh start
```
And run `msfconsole`
```bash
msfconsole
```
