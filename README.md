# arch-config

# add this stuff to i3 config file to make transparent
exec_always picom -f
exec --no-startup-id picom -CGb

# audio

pulseaudio-alsa/bluetooth/equalizer/jack 
alsa-utils

# package light
light -U 20
light -A 20
light -S 50
