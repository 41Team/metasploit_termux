# Metasploit Framework in Termux

![Metasploit 6 running](https://github.com/41Team/metasploit_termux/blob/master/screenshot/metasploit-screenshot.jpg)

  <details open>
  <summary><strong>Update Repository & Upgrade Package</strong></summary>

  ```bash
  pkg update && pkg upgrade
  ```
  </details>
  <details>
  <summary><strong> install package </strong></summary>

  ```bash
  pkg install unstable-repo

  pkg install wget

  pkg install ruby

  gem install bundler

  wget https://raw.githubusercontent.com/41Team/metasploit_termux/master/metasploit.sh

  chmod +x metasploit.sh

  ./metasploit.sh
  ```
  </details>
   
## After installation complete
Start `postgresql`
```bash
./postgresql_ctl.sh start
```
And run `msfconsole`
```bash
msfconsole
```
