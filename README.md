On your .bashrc (or .zshrc), put this lines :

    source ~/.git_prompt_maker.sh

    NONE="\[\033[0m\]"
    orange="\[\033[38;2;242;114;66m\]"

    PS1="$orange\u${NONE}@$orange\h$