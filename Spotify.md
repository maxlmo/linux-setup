# Spotify

* Set device scale for 4k in `/usr/share/applications/spotify.desktop`

[Desktop Entry]
Name=Spotify
GenericName=Music Player
Comment=Listen to music using Spotify
Icon=spotify-client
Exec=/bin/bash /usr/bin/spotify --force-device-scale-factor=1.5 %U
TryExec=/bin/bash
Terminal=false
Type=Application
Categories=Audio;AudioVideo;Player;Qt;
MimeType=x-scheme-handler/spotify;
X-Desktop-File-Install-Version=0.26
