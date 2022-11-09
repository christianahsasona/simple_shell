<h1> Oluwatosin Sasona & Abdulazeez Faruq </h1>
<hr>
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg" alt= "gates of shell" width="400px" height="400px"/>
<h3>Description</h3>
<p>A simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program was written entirely in C as a milestone project for ALX Africa Software Engineering.</p>
<h3>Installation</h3>
<p>Clone this repository into your working directory. For best results, files should be compiled with GCC and the following flags: -Wall -Wextra -Werror -pedantic -std=gnu89</p>
<h3>Usage</h3>
<p>After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.</p>
<h3>Interactive Mode</h3>
<p>In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.</p>
<h3>Non-Interactive</h3>
<p>In non-interactive mode, echo your desired command and pipe it into the program like this:

echo "ls" | ./shell</p>
<p>In non-interactive mode, the program will exit after finishing your desired command(s)</p>
<h3>Included Built-Ins</h3>
<p>Our shell has support for the following built-in commands:</p>
<table>
<tr><th>Command</th>
<th>Definition</th>
</tr>
<tr>
<td>exit [n] </td>
<td>Exit the shell, with an optional exit status, n.</td></tr>
<tr>
<td> env </td>
<td> print the environment </td>
</tr>
<tr>
<td>setenv [var] [value]</td>
<td> set an environment variable and value. if the variable exists, the value will be updated.</td>
</tr>
<tr>
<td>cd [dir] </td>
<td> Change the directory.</td>
</tr>
<tr>
<td>help [built-in]</td>
<td> Read Documentation for built-in. </td>
</tr>
</table>
<h3>Credits</h3>
<p> All code written by <a href="github.com/christianahsasona">Oluwatosin Sasona</a> and <a href="github.com/umarfaruq43">Abdulazeez Faruq</a></p>
