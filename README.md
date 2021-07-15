# Tmux Config

=============

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Tmux_logo.svg/1280px-Tmux_logo.svg.png" width="500px" />

## How to install

Refer to the [TMUX wiki](https://github.com/tmux/tmux/wiki) for any information including installation

## What is in this repository

This repository has the following structure

```
.
├── .gitignore              # Has all the git ignores
├── README.md               # You are reading this file
├── sessions                # Will contain all the session files
│   └── example.tmux.conf   # Example on how to setup your session
└── .tmux.conf              # Default configuration
```

## Using this repository

Basic use will be to close this repo at any place of choosing and then symlink the .tmux.conf file to ~/.tmux.conf

```bash
# replace the path with your chosen path
cd ~ && ln -s ~/.configs/tmux/.tmux.conf
```

For using sessions you can set-up a session using the example file and then run the following command

```bash
 # Use the path of where you cloned this
tmux -f ~/.configs/tmux/sessions/<your-session-file-name>.tmux.conf
```

## Future

I will keep adding to the repository as I feel the need for it.
