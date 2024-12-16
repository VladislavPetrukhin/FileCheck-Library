This is Filecheck Library. It compares files in directories (including nested dirs) and finds corruption.
<br/>
<br/>
Dependencies:<br/>
`sudo apt-get install meson vala gcc libgee0.8-devel`
<br/>
<br/>
Install:
<br/>
`cd FileCheck-Library`<br/>
`meson setup build`<br/>
`meson compile -C build`<br/>
`meson install -C build`<br/>
`export LD_LIBRARY_PATH="/usr/local/lib64"`<br/>
<br/>
To set the library path permanently:<br/>
<br/>
Open bashrc file:<br/>
`nano ~/.bashrc`<br/>
<br/>
Add the following line to the end of the file:<br/>
`export LD_LIBRARY_PATH="/usr/local/lib64:$LD_LIBRARY_PATH"`<br/>
<br/>
Save the file and apply the changes:<br/>
`source ~/.bashrc`<br/>
