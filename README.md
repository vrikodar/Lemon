# Lemon

![lemon](https://github.com/SxNade/Lemon/blob/main/Lemon.jpg)

`Lemon is a User Interactive bash program to search for basic/easy-wins privilege escalation vectors on Linux` 

*Before running in non-interactive reverse shell sessions **Spawn A TTY shell** --> https://netsec.ws/?p=337 * 

# Running Lemon

        $ git clone https://github.com/SxNade/Lemon
        $ cd Lemon
        $ chmod +x lemon
        
        $ ./lemon


![lemon](https://github.com/SxNade/Lemon/blob/main/lemon.gif)

*Also keep in mind that you may have to press **enter** after performing a single check from menu*

# On the Go one Liner

        curl https://raw.githubusercontent.com/SxNade/Lemon/main/lemon -o lemon ; chmod +x lemon ; ls -la lemon


# How Lemon Does not Crash your `shells`

*All the checks performed by lemon are done in background in a different proccess thread that is in a subshell which keeps your original shell intact and this can prevent your reverse shells from crashing **but keep in mind** you need a tty on your shell first to run the script properly which you can spawn using python or perl or any other of your choice*

# Option2 `tty_shell`

*this is a useful option that lets you jump between **system interactive shell** and the **script menu** back and forth, for example you Successfully Found a Attack vector and you want to try it the tty_shell option2 lets you drop into system shell and once you have tried it you can  type exit to exit the spawned shell and resume from the script panel.* 

# Option14 `console_clear`

*clears the terminal screen{**also automatically sets TERM variable**} and resumes the script execution this is useful to avoid overwhelming output produced by script all at once so you can perform one check and read the output and then clear the console to move onto next check* 


# Note

*Lemon by no means is a replacement for manual enumeration for privilege escalation, its just aimed at automating some basic checks that a user would do to search for easy wins.*

*Lemon searches for most common known misconfiguration, more options will be added in upcoming releases*
