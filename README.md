*Nautilus Backspace*
-----------------------
Brings back the Backspace shortcut to Nautilus

Installation
-----------------------
1) Install [Nautilus Python](https://wiki.gnome.org/Projects/NautilusPython) (`dnf install python2-nautilus -y ` in Fedora-based distributions)
 2) Download `Backspace-Back.py` and put it here: `.local/share/nautilus-python/extensions/`
(you might have to create this directory first)
3) Restart Nautilus (`killall -9 nautilus`)

`
dnf install python2-nautilus -y
mkdir -p .local/share/nautilus-python/extensions/ &&\
git clone https://github.com/oshaghi1/nautilus_backspace.git &&\
cd nautilus_backspace &&\
cp cp BackspaceBack.py .local/share/nautilus-python/extensions/
killall -9 nautilus
`

