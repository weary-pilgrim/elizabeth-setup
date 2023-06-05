# Elizabeth Setup

## Install iTerm2

This is a Terminal replacement.

- [Download it](https://iterm2.com/) and install it
- Never open the built-in Terminal program again. It stinks
- Skim the highlights section and the general section in the docs. (You might want to look at them again later after you have used it for a while)

You now have a new Mac app called `iTerm`. To run it, enter &#8984;+Space and then type `iTerm`.

## Install HomeBrew

This is a package manager for Mac command line programs. It knows how to install command line programs (like Python).

- Open a new `iterm` window
- Copy the command they have on their [homepage](https://brew.sh/)

    ![](img/homebrew-copy.png)

 - Paste it into your `iterm` window (and hit Enter)
 - Accept the default answer at any prompts
 - Follow any instructions the script gives you
 - Close your `iterm` window (you have to do this to make sure the Unix shell running in the terminal knows about new stuff)

You now have a new command-line program called `brew`.

## Install Oh My ZSH!

This is a Unix environment management doohickie that will make your life better in 10,000 ways.

- Open a new `iterm` window
- Copy the command on their [install page](https://ohmyz.sh/#install)

    ![](img/oh-my-zsh-copy.png)

 - Accept the default answer at any prompts
 - Follow any instructions the script gives you
 - Close your `iterm` window 

## Install VisualStudio Code

This is your code editor/integrated development environment (IDE).

- Go to [their website](https://code.visualstudio.com/)
- Click the `Download` button
- Open the `.zip` file that is downloaded
- Drag the `Visual Studio Code` application into your `Applications` folder
- Enter &#8984;+Space and then type `Visual Studio Code`
- When it starts
  - Open the Command Palette (&#8984;+Shift+P)
  - Type 'shell command' to find the Shell Command: Install 'code' command in PATH command

      ![](img/shell-command.png)

- If you have any `iterm` windows open, close them

You can launch code as you did above or by typing `code .` on the command line.
