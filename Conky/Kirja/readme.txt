----------------------------------------------------------------------------------------
Kirja System monitoring cat theme with XFCE4 logo
Created by Péter Varga
----------------------------------------------------------------------------------------
In English
----------------------------------------------------------------------------------------
This is a step-by-step video to the automatic install in a Debian base distribution:
https://www.youtube.com/watch?v=8-SdCpFgzt4
----------------------------------------------------------------------------------------
Automatic Install:
----------------------------------------------------------------------------------------
Use theese commands in the terminal (in Debian based distros (Ubuntu, Linux Mint...):
sudo apt-get install conky-all
sudo apt-get install git
git clone https://github.com/vpeter93/conky-themes

Copy the Conky folder to the /home/username folder.
You should change wlp3s0 to your Ethernet adapter name in .conkyrc file. 
Use ifconfig command in the terminal and copy your ethernet adapter name.
Change wlp3s0 to your ethernet adapter name in the code.
Run the install.sh in the terminal.
Conky will autostart.
----------------------------------------------------------------------------------------
Manual Install:
----------------------------------------------------------------------------------------
Use theese commands in the terminal (in Debian based distros (Ubuntu, Linux Mint...):
sudo apt-get install conky-all
sudo apt-get install git
git clone https://github.com/vpeter93/conky-themes

Copy the Conky folder to the /home/username folder.
You should change wlp3s0 to your Ethernet adapter name in .conkyrc file. 
Use ifconfig command in the terminal and copy your ethernet adapter name.
Change wlp3s0 to your ethernet adapter name in the code.
Copy the ConkyAutostart file to the /usr/share/applications and /etc/xdg/autostart 
folders. Copy the startconky.sh file to /bin folder.
Conky will autostart.
----------------------------------------------------------------------------------------
Uninstall:
----------------------------------------------------------------------------------------
Run uninstall.sh in the terminal and remove Conky folder from the home folder.
----------------------------------------------------------------------------------------
Magyarul
----------------------------------------------------------------------------------------
Kirja Rendszerfigyelő macska téma XFCE4 logóval
Készítette Varga Péter
----------------------------------------------------------------------------------------
A következő videó végigvezet az automatikus telepítésen:
https://www.youtube.com/watch?v=8-SdCpFgzt4
----------------------------------------------------------------------------------------
Automatikus Telepítés:
----------------------------------------------------------------------------------------
Írd be a következő parancsokat a terminálba (Debian alapú disztribúciókon (Ubuntu, Linux Mint...):
sudo apt-get install conky-all
sudo apt-get install git
git clone https://github.com/vpeter93/conky-themes

A Conky mappát egy az egyben tegyük a /home/felhasználónév mappába.
Ki kll cserélned a wlp3s0 szöveged a .conkyrc fájlban a saját ethernet adaptered nevére.
Hogy megtudd mi az ethernet adaptered neve használd a terminálban az ifoncif parancsot.
Futtasd terminálban az install.sh fájlt. Ez után automatikusan elindul a rendszerrel a conky.
----------------------------------------------------------------------------------------
Kézi Telepítés:
----------------------------------------------------------------------------------------
Írd be a következő parancsokat a terminálba (Debian alapú disztribúciókon (Ubuntu, Linux Mint...):
sudo apt-get install conky-all
sudo apt-get install git
git clone https://github.com/vpeter93/conky-themes

A Conky mappát egy az egyben tegyük a /home/felhasználónév mappába.
Ki kell cserélned a wlp3s0 szöveged a .conkyrc fájlban a saját ethernet adaptered nevére.
Hogy megtudd mi az ethernet adaptered neve használd a terminálban az ifoncif parancsot.
Hogy a conky automatikusan induljon a rendszerrel, a ConkyAutostart fájlt másoljuk
be az /usr/share/applications és a /etc/xdg/autostart mappákba, 
majd másoljuk a startconky.sh fájlt a /bin mappába.
----------------------------------------------------------------------------------------
Eltávolítás:
----------------------------------------------------------------------------------------
Futtasd az uninstall.sh fájlt a terminálban és töröld a home mappából a Conky mappát.
