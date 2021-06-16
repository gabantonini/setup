## Visual Studio Code

### Installation

Let's install [Visual Studio Code](https://code.visualstudio.com) text editor.

Copy (`CTRL` + `C`) the commands below then paste them in your terminal (`CTRL` + `SHIFT` + `v`):

```bash
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt update
sudo apt install code
```

:point_up: This command will ask for your password with: `[sudo] password for <username>:`.

Don't panick! Calmly type your password key by key. You won't have a visual feedback (like little `*`), that's **perfectly normal**, keep on typing. When you're done, hit `Enter` :muscle:.

### Launching from the terminal

Now let's try to launch your VS Code from **the terminal**:

```bash
code
```

Now, pin VS Code to your Dock by righ-clicking on the icon to bring up the context menu and choosing "Add to Favorites":

![](images/ubuntu_dock.png)

You can move forward!