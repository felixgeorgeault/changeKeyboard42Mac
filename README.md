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

If you want to know how the values will look without having to log out of your session, here is a website that will help you get the right values for your needs -> [keyboardSpeedCalculator](https://mac-key-repeat.zaymon.dev/)
Finally, log out of the session and it will be affected. Enjoy !

PS: It is not attached to your session but to the computer. So if you change from a computer to another it won't work. But if you are tired to change the settings everytime you log in on the same pc, well you won't have to anymore. 
And of course if you log int into another pc, you can put the same commands it will also work !

## Credit
ZaymonFC was the one who made the website. Here is his [github link](https://github.com/ZaymonFC).
