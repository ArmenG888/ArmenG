# The language 
<ul>
<li><h3>Keyboard</h3>
  <h4>You can click or type things on victims computer</h4>
Will type hello and bye on the victims computer
<pre>
1. keyboard:"
2. Hello
3. bye
4. ";
</pre>
<h4>Pressing buttons or hotkeys, need to be placed inside `button_name`</h4>
<pre>
1. keyboard:"
2. `ctrl + n`
3. `enter`
4. `alt + f4`
5. ";
</li>
  
<li><h3>Read</h3>
<h4>Read files and takes infinite amount of arguments separted by a commma</h4>
<pre>
1. read("test.txt")
[Output]:
test.txt content
</pre>
<h4>Read multiple files (infinite amount)</h4>
<pre>
1. read("file_name", "filename_2")
[Output]:
:file_name:
file content
:filename_2:
file 2 content
</pre>
</li>
  
<li><h3>Delay</h3>
<h4>Takes on argument in seconds</h4>
<h4>This example will delay for one second</h4>
<pre>1. delay(1)</pre>
</li>

<li><h3>CD</h3>
<h4>Changes directory optional one argument which is directory name .. is going back</h4>
  <h4>If not arguments argument will be the current directory</h4>
<pre>
1. cd documents
[Output]:
C:/users/User/documents/
2. cd ..
[Output]:
C:/users/User/
3. cd 
[Output]:
C:/users/User/
</li>  
  
<li><h3>Power</h3>
<h4>Controling the computers power, restarting, shutting down, and logging out the user (sleep)</h4>
<pre>
1. power("shutdown")
[Output]:
Shutting down the pc
2. power("sleep")
[Output]:
Computer is going on sleep
3. power("restart")
[Output]:
Restarting the pc
4. power(0)
[Output]:
0 is a invalid argument, (shutdown, restart, sleep)
</pre>
</li>
  
<li><h3>Python</h3>
<h4>Running python scripts</h4>
<pre>
1. python: "
2. print("hello world")
3. ";
[Output]:
hello world
</pre>
</li>
  
<li><h3>CMD</h3>
<h4>Anything other will be interpurted as a cmd command</h4>
<pre>
dir
</pre>
</li>
</ul>
