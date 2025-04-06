<pre>
Deps : sway waybar wmenu foot swaylock swaync blueman pavucontrol 
	network-manager-applet noto-fonts thunar xfce4-appfinder 
	brightnessctl grim nwg-look gammastep xwayland

Keyboard Cheat :
Main Super/Win
Win + [Nav] 			- Focus
 Alt (+ Shift) + Tab		- Focus (Invert)
 Win + Space 			- Focus (tab|window)
Win + Shift + Space 		- Toogle (tab|window)
Win + Shift + [Nav] 		- Move (tab|window)
Win + f 			- Fullscreen
Win + r 			- Resize window/aplikasi
				  Enter atau Esc untuk keluar
Win + e 			- thunar (File Manager)
Win + d 			- wmenu-run (Run)
Win + a 			- xfce4-appfinder (App drawer)
Win + Enter 			- foot (Terminal)
Win (+ Shift) + minus 		- Scratchpad (minimize program)
Win + Shift + l 		- Lockscreen 
				  (default: langsung ketik password login!)
Win + Print(PrtSc) 		- Screenshot, 
				  (default: tersimpan ke ~/Pictures/ )
Win + Shift + q 		- Menutup program (global),
				  alternatif keluar menggunakan menu 
				  aplikasi (Ctrl + q, Ctrl + d).
Win + Shift + c 		- Reload Sway
Win + Shift + e 		- Keluar Sway

Untuk pemindahan Tab program bisa menggunakan pointer (tab drag), 
 Win + klik kiri kursor, Win + Shift + [Nav].
Win + Shift + [Nav] juga digunakan untuk melakukan split window jika ada
 lebih dari satu tab. Arahkan keluar tab untuk split dan ke tab lain 
 untuk gabung, sedangkan pada mode window digunakan untuk menggesernya.

Tips tambahan :
untuk Login Sway dari TTY gunakan 'dbus-run-session sway' lalu untuk pengaturan 
 sesi dan power gunakan 'systemctl -i sleep|reboot|poweroff' dan 'loginctl' dari 
 terminal atau modifikasi/menambahkan menu pada waybar.

Fix Thunar > Open Terminal here
$ echo "TerminalEmulator=foot" > ~/.config/xfce4/helpers.rc

Untuk dokumentasi lain bisa melalui 'man sway' dan untuk pengaturan default 
 dari Sway dan lainnya ada pada direktori /etc/xdg/. 

</pre>
