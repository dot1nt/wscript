# wscript
Simple script for creating Firefox webapps

## Usage
```
git clone https://github.com/dot1nt/wscript.git && cd wscript
chmod +x webapp

./webapp create name url
./webapp remove name

Example:
./webapp create Netflix https://netflix.com
./webapp remove Netflix
```

Webapps are created with a custom userChrome.css without navbar. The profile gets copied into ~./var/webapps and a .desktop file is created in ~.local/share/applications/.
