# The-Art-of-.bashrc

# .bahsrc file

```bash
# alias for ls 
alias ll = 'ls -als'

# alias to create a directory and cd into it
mkcd() {
  mkdir -p "$1" && cd "$1"
}

# Aliases to protect against overwriting
alias cp='cp -i'
alias mv='mv -i'
alias rm='rm -i'
```

# Usage

Source .bashrc file 

```bash
source ~/.bashrc
```
