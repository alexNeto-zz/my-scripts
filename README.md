# My scripts

Here is some scripts to run some commands that is very unlikely that I will remember them or some 
I'm too lazy to type and make more sense to use a very unintuitive script like this one.

If you want to use these scripts just put it in the `/home/$HOME/bin` folder or create a link there.

## dkr

Some docker commands

1. Remove dangling images (the ones that apeas as <none> when you use `docker images`)
    ```bash
    dkr dd
    ``` 

## gut
Some git commands I use everyday

1. Show status 
    ```bash
    gut s
    ```
1. Sync the actual branch
    ```bash
    gut sync
    ```
1. Sync to some specific branch
    ```bash
    gut sync-to [branch-name]
    ```
1. Push to the actual branch
    ```bash
    gut p
    ```  