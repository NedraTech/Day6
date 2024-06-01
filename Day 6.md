# script installation

- to install script to github git clone <link_of_script_from_github>
Wget
- is used to install files in any website.
- wget {file_link}
## Linux Process & services
- Linux process is used to see running  programs and we can stop that program
- we use ps[option]
- ps -> forprocess running in the shell
- ps -A -> to see all running process
- pa -u [username] ->to see  process for this user name
- PID means - process id
- to stop process
- kill [option]  [PID]
- More on kill
- kill -19 [PID] -> t stop the process that running by this id
- kill -18 [PID] -> to stop and resume the process by this id
## to kill on htop
- to search F3
- to kill F9
- to out htop F10
## Null device
- we get in /dev/null
- it used to ignore the error but the error doesn't fix.
- STDERR = 2 -> to see correct out put
- STDOUT = 1 -> to see thee errorh
## Foreground / background
- Foreground -> is running in the front of Linux. in this case we waited to complete the program.
- Background -> it we run another program and the other program is running in the back of our program.
- to run in the background -> for example :- nano first & {at the end of the command we write &}
## symbolic linking
- a process of creating a shortcut for an existing folder or file.
- ln -s file_Path file_Name
## Alias
- to give  a name for  some bunch of (a long) command.
- alias name = "command"
- for configuration file:-
- Bash =~/.bashrc
- Zsh=~/.zshrc
- fish=~/.config/fish/config.fish

## Tmux
- used to classify the terminal
## Find
- to search files/folders/music/videos
- find {search path} {options} {search word}
- find / -name "linux"
- find /home -perm 777
- find -type f (to find files) || find type d(to find directories)
## script modules
- scripts are made with scripting(programming) language like[Python, bash, go, ruby . . .]
1. Python- pip install -r <modulename>
2. Go - go install <modulename>
3. Ruby - gem install <modulename>

_ Python installation______
- pip install term.
- if the package is already installed:
      - pip install -r requirementsz.txt
______Go package installation_
- old version 
- new version
1. old version
    - go get github.com:capotej/groupcache-db-experiment.git
2. new version 
     - go install github.com/lc/gau/v2/cmd/gau@latest
     - moving file to /usr/bin(defult download place is /home/rexder/go/bin
     - sudo mv filename /

