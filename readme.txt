1. Use Helvum to create connection.
2. Use qpwgraph to save as 'bt-only-patchbay.qpwgraph' the connection.
3. Edit 'pipewire.sh' script using above configuration file name.
4. Copy 'bt-audio.desktop' to /usr/share/applications/bt-audio.desktop.
5. Copy all to pipewire dir inside opt dir.

```
cd /tmp
git clone https://github.com/prasanthc41m/pipewire.git
sudo cp pipewire/bt-audio.desktop /usr/share/applications/
sudo cp -r pipewire /opt/
```
