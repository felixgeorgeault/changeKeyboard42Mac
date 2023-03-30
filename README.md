# Change keyboard speed on your 42 mac.

## If you are suffering from the slowness of the 42 keyboard, this is for you !

To do so, you only need 2 commands which are down below.

1. The "initialKeyRepeat". It is how much time the keyboard will take before entering the keyRepeat mode. You can modifiy the INT at the end of the command, the smaller, the faster.
```
defaults write -g InitialKeyRepeat -int 10
```

2. There is also the keyRepeat speed. It is how much time the key will be repeated in a second kind of...Like before, just change the int on your preferences, again, the smaller the faster.
```
defaults write -g KeyRepeat -int 2
```
