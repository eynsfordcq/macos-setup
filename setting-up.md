## Basic Settings 


### Separate Natural Scroll
This allows you to turn on natural scroll for touchpad and off for mouse
[github/UnnaturalScrollWheels](https://github.com/ther0n/UnnaturalScrollWheels)


### Snap To Edges 
This allows you to snap windows when you move to the edge, just like windows.
[github/Rectangle](https://github.com/rxhanson/Rectangle)


### Dock Appear Delay
This settings changes the delay of the dock if you set it to auto-hide
```
# instant
defaults write com.apple.dock autohide-delay -float 0; killall Dock

# revert to default
defaults delete com.apple.dock autohide-delay; killall Dock
```
