# Sublime-MCFunction
A Sublime Text 3 package that adds syntax highlighting and other functionality for Minecraft's function file format (`.mcfunction`) added in the 1.12 prereleases.

![Demonstration of highlighting](pics/demo1.png)  
*Shown using Monokai*

Highlights comments, commands, entity selectors, numbers, namespaces, NBT, `this.sort.of.thing`, blockstates, and more (depending on color theme support).

Points out errors in NBT syntax, as well as invalid forward slashes at the beginnings of lines.

You can add special highlighting to comments by beginning them with `#~`.

# Package Control Installation
***Recommended!** Among other things, Package Control will automatically keep this package up-to-date.*

0. If you have already installed MCFunction manually, delete the manual installation. Sublime may warn you that it is unable to find the package; this is fine. You'll be adding it back in a moment.
1. If you haven't already, install Package Control. https://packagecontrol.io/installation
2. Follow Package Control's instructions for installing packages. https://packagecontrol.io/docs/usage
   1. Open the Command Palette with `Ctrl+Shift+P` or `Cmd+Shift+P`.
   2. Select the command "Package Control: Install Package".
   3. Select "MCFunction" from the list of installable packages. Don't see it? Make sure that you have the latest version of Sublime Text 3, and that you have completed step 0.

# Manual Installation
1. Download the repository. You can do this by using Git or by [downloading it as a `.zip`](https://github.com/AjaxGb/Sublime-MCFunction/archive/master.zip).
2. Open the `Packages` folder by selecting "Preferences" > "Browse Packages..." in Sublime Text.
3. Place the (extracted) repository folder in the `Packages` folder.
