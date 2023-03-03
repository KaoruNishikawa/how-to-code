FROM jekyll/jekyll:latest

RUN apk add gnupg curl \
    && curl -o $HOME/.bashgit https://raw.githubusercontent.com/oyvindstegard/bashgit/master/.bashgit \
    && echo "if [ -f $HOME/.bashgit ]; then . ~/.bashgit; fi" >> $HOME/.bashrc
