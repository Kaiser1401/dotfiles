# Dotfile with Prompt and zshlocal
> original from #https://github.com/cornerman/dotfiles

    clones below are now submodules, installs still have to be done

    cd #Change to Home Folder
    git clone http://10.10.1.190/al_SW_Team/dotfiles  # Clone to Home
    cd dotfiles 
    ./linkdotfiles.sh # Run the script to link your dotfiles to this folder
    sudo chsh -s /bin/zsh <user> # Change your default shell to zsh
    
    cd dotfiles 
    git clone https://github.com/cornerman/prompt-hjem
    cd prompt-hjem
    sudo make install

    cd dotfiles 
    mkdir progs  
    cd progs  
    git clone https://github.com/junegunn/fzf  
    cd fzf  
    ./install

