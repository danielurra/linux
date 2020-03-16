# Linux
It has been a while since the times when I was learning Linux<br>
And that's the reason why I decided to review a few important concepts<br>
and also to get up to date on current trends in the sysadmin field<br>
Most of the time I work with CentOS<br>
## Locate<br>
<img src="/sysadmin/images/filtering-locate-01.png" alt="filtering locate"><br>
## Grep<br>
Grep is a tool used to search for certain expressions in data <br>
these expressions can be "<b>Plain Text</b>" or those known as "<b>Regular Expressions</b>" <br>
And the input for this command could be either an existent file or the output <br>
coming from another command (redirecting using pipe) <br>
<br>
See below an example of using "grep" to find and highlight the word "bin" (plain text) inside the <br>
file "passwd" that is located inside the directory "/etc":<br>
<img src="/sysadmin/images/grep-01.png" alt="filtering locate"><br>
<br>
Another good example could be to list all the files and folders inside /etc <br>
and using grep to filter the output of "ls" to only files which start with the letter "d" <br>
that way we will only see a list of directories, see the screnshoot below <br>
<img src="/sysadmin/images/grep-and-reg-expressions-01.png" alt="grep and regular expressions"><br>
As you can see I had to cut off the list because it is too long <br>
<br>
If you are wondering how many directories we have, then we can redirect <br>
the output to "wc" (word count) including the option "-l" to count the amount of lines <br>
<img src="/sysadmin/images/grep-and-reg-expressions-02.png" alt="grep and regular expressions 02"><br>
<br>
## Terminal Emulator<br>
By the way for those of you wondering about the terminal emulator I prefer<br>
and which color scheme was selected, see below screenshot (SecureCRT)<br>
<img src="/sysadmin/images/SecureCRT-emulation-linux-ANSI-color.png" alt="securecrt"><br>
<br>
## $PATH (environment variable)<br>
$PATH is an environment variable used to specify a set of directories where executable programs are located<br>
In general either for Windows, Linux or Mac, each executing process or user session has its own PATH <br>
<b>echo $PATH | tr ':' '\n' </b><br>
<img src="/sysadmin/images/echo-path.jpg" alt="path"><br>
