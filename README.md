# somelittlescripts
Some little scripts i wrote

smartedit:
    
    usage: smartedit <path/to/file> (<editor> <authenticator>)

    description: if the file that you want to edit does not exist, or requires root privileges then
    it creates the full path to file and authenticates if needed

    what to modify if you want to use it: at the top of the script you can specify your editor to be 
    used and your authenticator (defaults are neovim and doas)

    plans: autodetect filetype and use an editor according to that

