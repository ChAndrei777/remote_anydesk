# Install anydesk
Install from official site: https://anydesk.com/en/downloads/linux

# Edit gdm3 config
Edit file /etc/gdm3/custom.conf:

    WaylandEnable=false
        AutomaticLoginEnable = true
        AutomaticLogin = panda

More detailed: https://askubuntu.com/questions/1131921/anydesk-remote-server-display-not-supported-e-g-wayland