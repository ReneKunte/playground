# My first repository 
I'm René Kunte and this is my git playground.

Remember: status, add, commit, push :clap:

## General information

Basis authentication using a password to Git is deprecated and will soon no longer work. Beginning August 13, 2021 GitHub will no longer accept account passwords when authenticating Git operations. GitHub recomments token-based authentication, but you may continue using SSH keys.

--> I'm familiar using SSH, so I'm staying with SSH :smile:

## Essential commands
**Display the history of commits.**

    git log

**Revert back all changes since the last commit.**

    git checkout .

**Revert all changes on a specific file since the last commit.**

    git checkout [FILENAME]

**Display the last changes on a specific file since the last commit.**

    git diff [FILENAME]

**Remove all unexpected files in this project**

    git clean -dfx

**Add all files and make a commit at the same time**

    git commit -am [MESSAGE]