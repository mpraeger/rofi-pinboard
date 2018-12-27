Python3 script to search through pinboard bookmarks via rofi and open the URL in your default browser.

```
Usage: rofipinboard.py [OPTIONS] COMMAND [ARGS]...

  Main function

Options:
  --help  Show this message and exit.

Commands:
  all    Get all bookmarks
  setup  Setup Pinboard
  url    Get URL for one bookmark
```

## Prerequisites
Please either install the required python packages or ensure that they are installed.
```
$ pip install -r requirements.txt
```

Rofi also needs to be installed.

## Installation
Place `rofipinboard.py` and `rofi-pinboard` somewhere in your PATH. Afterwards execute `rofipinboard.py setup` to store your Pinboard API token.

## Using with rofi
You will have to call the included bash script, which is going to take care of the rest.
