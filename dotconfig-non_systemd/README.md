for Sway standard or full <br>
<pre>
core deps {
  sway-backgrounds,
  sway-notification-center,
  sway,
  swaybg,
  swayidle,
  swayimg,
  swaykbdd,
  swaylock,
  waybar
}
  
recommended deps { 
  thunar*, --file_manager -waybar -sway
  polkit-gnome, --optional -sway
  xfce4-appfinder, --app_launcher -sway
  nwg-look, --optional
  gnome-disk-utility, -waybar 
  /bin/firefox, -waybar
  gammastep, -waybar
  brightnessctl, -waybar -sway
  blueman, -waybar -sway
  pavucontrol, -waybar -sway
  grim, -sway
}

Core Hotkey 
  main Win|Super
  Win + Enter  - Terminal|foot,
  Win + e  - Thunar,
  Win + d  - Launcher,
  Win + a  - Notification Center,
  Win + x  - Toggle Tabbed (Maximize | Unmaximize)
  Win + PrintScr - Screenshot by grim ~/Pictures/
  ... Read sway/config
</pre>

OS Devuan, Void|Artix, *non-systemd plug-&-play
