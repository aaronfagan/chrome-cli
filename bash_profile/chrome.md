Add the following to your `~/.bash_profile` and run `source ~/.bash_profile`.

```
function chrome() {
    BROWSER='Google Chrome'
    HOME_URL='https://www.google.ca/'
    if [ ! -z "$1" ]
        then open -a "$BROWSER" "$1"
    else
        if pgrep -f "$BROWSER" >/dev/null 2>&1
            then open -a "$BROWSER" "$HOME_URL"
        else
            open -a "$BROWSER"
        fi
    fi
}
```