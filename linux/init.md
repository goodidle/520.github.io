## /etc/bashrc
```bash
export HISTSIZE=3000000
export HISTTIMEFORMAT="%F %T "
export PROMPT_COMMAND="history -a; $PROMPT_COMMAND"
unset HISTCONTROL
```

## ~/.bash_profile
```bash
export PS1="\n[\e[1;32m\u\e[1;31m@\e[1;36m\h\e[0m \e[1;31m\t\e[0m] : \e[1;35m\w\e[0m\n$?> "
```
