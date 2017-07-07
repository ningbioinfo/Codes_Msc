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

  - to glimpse files

    - ``

## Python codes
