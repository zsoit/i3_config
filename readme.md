# ---custom by jakun settings ----


## i3/config

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


#remove bar 
for_window [class="^.*"] border pixel 2, title_format " %title"
~                                                                

## i3status

sudo cp /etc/i3status.conf ~/.config/i3/i3status.conf
sudo chmod 777 ~/.config/i3/i3status.conf

sudo apt instal fonts-font-awesome -y


## gtk 3-0

~/.config/gtk-3.0/settings.ini

[Settings]
gtk-icon-theme-name=Ubuntu-mono-dark
gtk-theme-name=Yaru-Red-dark
gtk-application-prefer-dark-theme=0



~                                                                                                       
~        
