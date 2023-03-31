# Change keyboard speed on your 42 mac.

## If you are suffering from the slowness of the 42 keyboard, this is for you !

To do so, you only need 2 commands which are down below. 

1. The "initialKeyRepeat". It is how much time the keyboard will take before entering the keyRepeat mode. You can modifiy the INT at the end of the command, the smaller, the faster.
```
defaults write -g InitialKeyRepeat -int 12
```

2. There is also the keyRepeat speed. It is how much time the key will be repeated in a second kind of...Like before, just change the int on your preferences, again, the smaller the faster.
```
defaults write -g KeyRepeat -int 2
```

## Automatically apply the changes on a **new computer** ?
If you don't want to write theses commands everytime you change from a pc to another. You can put theses into your '.zshrc' config file. Just like so:
```
echo "defaults write -g InitialKeyRepeat -int 12" >> ~/.zshrc;
echo "defaults write -g KeyRepeat -int 2" >> ~/.zshrc;
zsh;
```

Then if you switch to another computer, you will only have to :
- Log in, open the terminal (so that the '.zshrc' file will execute the commands).
- Log out from your session.
- Log back in.

And there you go ! The changes will be permanent **on this computer**.

## Pros
If you have opened the terminal at least once and loged out of the session on a computer, you won't have to do it ever again on this computer.

## Cons
If you swap from a computer to another, you have at least to log out once. But I think it is not that bad because then you don't have to change theses settings ever again on that computer, so if you are used to go on a specific computer you are good to go.

## Speed values generator
Here is a website that will help you find the right values for you without having to log out the computer each time you want to see the changes -> [keyboardSpeedCalculator](https://mac-key-repeat.zaymon.dev/)

## Credit
ZaymonFC was the one who made the website. Here is his [github link](https://github.com/ZaymonFC).
