# Some codes of the past year

## These codes are really basic, and they are here in case I forget them for the next two months of vacation. ;)

## Mac set up

1. Terminal decoration

  - oh-my-zsh

2. Atom decoration

  - Themes

    - atom-material-ui

  - Packages

    - ask-stack
    - autocomplete-python
    - busy-signal
    - file-icons
    - highlight-line & highlight-selected
    - intentions
    - linter (linter-markdown & linter-python & linter-ui-default)
    - markdown-preview-plus
    - markdown-writer
    - minimap
    - tidy-markdown
    - wordcount

3. Useful apps (Hacked address is in my Google drive)

  - Photoshop CC 2017
  - OmniGraffle
  - texmaker
  - Airmail

4. Nerdy stuffs

  - Homebrew
  - R (the latest one) & Rstudio (the latest one)
  - Python (2.7.x & a latest one)

    - Anaconda
    - iPython (Jupiter)
    - virtualenv
    - library such as numpy, scipy, panda, Biopython and etc

## Common and useful codes

1. Transfer documents among VMs

  - `sftp -i publickey username@IPaddress`

    - while in `sftp` mode, use `put` and `get` to transfer files

  - `rsync -avP username@IPaddress:path/to/the/target/file(s) local/path/to/put/the/file`

2. VM configs

  - config file is in `~/.ssh/` directory

    - formats are like :

      ```
      Host rstudio
      Hostname 129.127.107.217
      User ning
      ServerAliveInterval 60 # this is for preventing the VM from auto-exit in short time
      ```

  - publickeys to access VMs such as `hub` and `hub.pub` are in `~/.ssh/` as well

  - custom shortcuts are by editing the `~/.bashrc` file such as:

    ```
      alias ll='ls -lh'
      alias tofast='cd /fast/users/a1692215'
    ```

3. Useful bash codes

  - hostname or computername setup of Terminal

    - `sudo scutil --set HostName <name-you-want>`
    - 'sudo scutil --set ComputerName

      <name-you-want>'</name-you-want>

  - to glimpse files

    - usually with `head` and `tail` for text file and `|zcat` with zip file
    - Full document check using `less` or `cat`

  - to create a file

    - using `touch`
    - using `vim` to directly write a text

  - to manipulate column file like .bed files

    - `awk` and `cut` are the best
    - sometimes `comm` and `diff` is good
    - further should use `bedtool`

  - [TMUX](https://tmux.github.io/)

    - tmux is a system that preventing the VM from closing and run command in the background
    - to check tmux session: `tmux list-session`
    - to create a session: `tmux new-session -s <session-name>`
    - to go to a session: `tmux attach-session -t <session-name>`
    - to leave a session: `tmux detach`
    - during a session, add a pane: `ctrl+B` then `%(shift+5)`, to switch pane using left or right
    - during a session, to scroll: `ctrl+B` then `[`, and exit with `ESC`

## Python codes

### Use LiClipse to write code and quick run

### but when dealing with long script should use ATOM

1. Set parameters for code

  - [`argparse`](https://docs.python.org/2/howto/argparse.html) library

2. Biodata analysis

  - [`biopython`](http://biopython.org/DIST/docs/tutorial/Tutorial.html) library

3. easy visual

  - [jupyter(ipython notebook)](https://jupyter.org/)

4. 1
