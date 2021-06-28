# An intelligent vim - neovim

One of the great advantage of the vim is, it is very flexible and smart customizable.
Here we are going to install a new version of vim called `neaovim` and do some setup to make it look like an actual IDE.
</p>

The ***neovim*** can do many things. Here i made a little configuration that make the vim as i like to be.

REMEMBER : you need a basic understanding of vim commands

## **Steps to install**

1) git clone to me.

```bash

git clone https://github.com/OneSecCyber/intellij-vim.git

```

2) run this to do required changes in your neovim/nvim configuration files

```bash
cd intellij-vim

make

```
NOTE: After this operation, the nvim should open automatically

REMEMBER : The second steps will not install anything. instread, it will make changes in configuration files.

3) Install the required plugins

```bash

:PlugInstall

```
NOTE: I hope, you know what i mean by `:`

4) Install the ***Coc*** IDE

```bash

:CocInstall coc-python coc-yaml coc-css coc-html coc-json coc-tsserver

```
INFO : you can install a lot of coc pllugins, see the nvim documentation for coc

5) If its all gone well, you can feel the power of nvim.
	To test, open some file like :


```bash

nvim test.py

```


## **troubleshooting**

1) if you have any problem while doing this, open nvim and do THIS to find the issue.

```bash

:checkhealth

```

2) If you have any problem in installing `coc` ,  it may be because of your installed `nodejs` is out of date - requires : node version >=12 
<p>
to check that :

```bash

:CocInfo

```



**This is just a beginning, we can do a lot with nvim**

##### If you like to program using phone, Install the termux and play with this powerfull "IDE" 
