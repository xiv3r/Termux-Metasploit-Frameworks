## Auto Install
```
apt update && apt upgrade -y && apt install wget -y && wget -qO- https://raw.githubusercontent.com/xiv3r/Termux-Metasploit-Frameworks/refs/heads/main/install | sh && msfconsole
```

# (Opt) Update
```
cd && rm -rf $PREFIX/opt/metasploit-framework && wget -qO- https://raw.githubusercontent.com/xiv3r/Termux-Metasploit-Frameworks/refs/heads/main/install | sh && msfconsole
