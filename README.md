# zsh_profile_and_alias

How to make alias to use in your terminal for macOS Catalina version 10.15.5


--- Open a terminal window --- 

1. Go into your home directory 

`cd ~`

2. Check your zsh version 

`zsh --version `

3. Open your zsh in a nano or vi document

`vi ~/.zshrc`


4. write the alias you wish to create 

    - Exemple : shortcut for a server 
     `alias NAMEYOUCHOOSE ='ssh your.servers@adress'
    - Exemple : to sleep your display 
     `alias sleepnow="pmset displaysleepnow"`


5. Source your new zsh profile or restart your mac

`source ~/.zshrc`
