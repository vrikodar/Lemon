# Lemon

![lemon](https://i.pinimg.com/originals/77/fd/43/77fd43ae375e3630e6d0502844f25ee2.png)

**Lemon is a User Interactive bash program to search for basic/easy-wins privilege escalation vectors on Linux**

*Before running in non-interactive reverse shell sessions **Spawn A TTY shell** --> https://netsec.ws/?p=337 * 

# Running Lemon

        $ git clone https://github.com/SxNade/Lemon
        $ cd Lemon
        $ chmod +x lemon
        
        $ ./lemon -h or ./lemon --help    {run to see other options}


# On the Go one Liner

``` curl https://raw.githubusercontent.com/SxNade/Lemon/main/lemon -o lemon ; chmod +x lemon ; ls -la lemon ```

# TIP

**Its recommended that you catch your shells using rlwrap along with netcat this makes your shells more stable and allows you to go through command history as in your typical linux shell with UP and DOWN arrows**

*rlwrap can be installed with*
                
                        $ apt install rlwrap
                        
                Listening for incoming connections with rlwrap --> rlwrap nc -lp <port>

*same goes for bind shells*

![lemon](https://github.com/SxNade/Lemon/blob/main/lemon.gif)

*Also keep in mind that you may have to press **enter** after performing a single check from menu*

# Note

*Lemon by no means is a replacement for manual enumeration for privilege escalation, its just aimed at automating some basic checks that a user would do to search for easy wins.*

*Lemon searches for most common known misconfiguration, more options will be added in upcoming releases*
