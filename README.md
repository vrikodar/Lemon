# Lemon

![lemon](https://github.com/SxNade/Lemon/blob/main/Lemon.jpg)

`Lemon is a User Interactive bash program to search for basic/easy-wins privilige escalation vectors on Linux` 

**LEMON IS STILL UNDER ACTIVE DEVELOPMENT**

*contributions are welcomed*

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

# Note

*Lemon by no means is a replacement for manual enumeration for privlige escalation, its just aimed at automating some basic checks that a user would do to search for easy wins.*

*Lemon searches for most common known misconfiguration, more code is yet to be added and reformatted*
