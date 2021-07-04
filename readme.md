# ---custom by jakun settings ----


## 1 i3/config

#workspace switches
bindsym Control+$mod+Left workspace prev
bindsym Control+$mod+Right workspace next

#kill focused windows
bindsym $mod+q kill

#font
font pango:DejaVu Sans Mono 12


bar {
position top
status_command i3status -c /home/achtelik/.config/i3/i3status.conf
}

## 2 i3status

sudo cp /etc/i3status.conf ~/.config/i3/i3status.conf
sudo chmod 777 ~/.config/i3/i3status.conf

sudo apt instal fonts-font-awesome -y


~                                                                                                       
~        
