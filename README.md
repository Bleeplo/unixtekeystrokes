# unixtekeystrokes
Unixtekeystrokes is a custom python module for Linux/Unix systems. That allow for custom macros. Using xte.

Rough description of what this script has:
1.Artificial keystrokes
2.Artificial mouse movements/actions
3.Keystroke detection -> Do this & kill listening
4.Keystroke 1 -> do something; Keystroke 2 -> Kill listening


So this does require XTE. Here is how to install xautomation on other Linux distros.
Debian: 
sudo apt-get update
sudo apt-get install xautomation

Ubuntu:
sudo apt-get update -y
sudo apt-get install -y xautomation

Arch: 
Visit this link and read it: https://archlinux.org/packages/community/x86_64/xautomation/

**(Manjaro: use "Add/Remove software" and search up "xautomation")**

Once that is done. You are going to need to have the pyxhook module (pip install pyxhook) for the keystroke detection to work.



Now that all the requirements are setup. Find where your Python directory is located. Specifically where your modules are located.
For example, Manjaro users. Your Python module directory would be something like " /home/user/.local/lib/python3.9/site-packages/"

And that should be all there is to the setup.
 Why don't I make this for pip? Because I don't really want to. I just don't care enough to do so.
