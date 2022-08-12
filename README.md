Some shell utils that I have found useful in my work. `${HOME}/.local/bin` is a good place to save these
shell scripts. Also adding `[[ -d "${HOME}/.local/bin" ]] && export PATH="${PATH}:${HOME}/.local/bin"` in your
shell (bash/zsh...this won't work with sh) initialization script is a good idea.
