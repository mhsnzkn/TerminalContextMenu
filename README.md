# Add Windows Terminal to Context Menu
This repository contains the files for adding Windows Terminal to the right click context menu. Windows Terminal is opened for the current directory.<br> <b>Windows Terminal is needed to be installed before running this project.</b>
## How to install
<ol>
<li>Open src folder</li>
<li>Run install.bat</li>
<li>Click Yes for the registry edit confirmation</li>
<li>Done</li>
</ol>
<p><b>P.S.</b>if you face 'Windows cannot access the specified device, path, or file. You may not have the appropriate permissions to access the item.' error</p>
<p>In wt.reg file change the following lines:</p>
<p>%USERPROFILE% → C:\Users\[userName]</p>
<p>%LOCALAPPDATA% → C:\Users\[userName]\AppData\Local</p>
