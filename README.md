This is Filecheck Library. It compares files in directories (including nested dirs) and finds corruption.
<br />
<br />
Dependencies:
sudo apt-get install meson vala gcc libgee0.8-devel
<br />
<br />
Install:
<br />
cd FileCheck-Library<br />
meson setup build<br />
meson compile -C build<br />
sudo cp build/libfilecheck.so /usr/local/lib <br />
sudo cp build/filecheck.vapi ../FileChecker (cp to the GUI app folder)<br />
sudo cp build/filecheck.h ../FileChecker (cp to the GUI app folder)<br />
export LD_LIBRARY_PATH="/usr/local/lib"<br />
