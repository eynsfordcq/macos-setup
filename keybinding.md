## Keybindings

### Home and End Behavior like Windows

There are two reference that does this:

Basic:
[StackExchange](https://apple.stackexchange.com/questions/16135/remap-home-and-end-to-beginning-and-end-of-line)

A more complete version:
[github/DefaultKeyBinding.dict](https://gist.github.com/trusktr/1e5e516df4e8032cbc3d)

```bash
mkdir -p $HOME/Library/KeyBindings
echo '{
"\UF729" = "moveToBeginningOfLine:"; /* Home */
"\UF72B" = "moveToEndOfLine:"; /* End */
"$\UF729" = "moveToBeginningOfLineAndModifySelection:"; /* Shift + Home */
"$\UF72B" = "moveToEndOfLineAndModifySelection:"; /* Shift + End */
}' > $HOME/Library/KeyBindings/DefaultKeyBinding.dict
```


