# My Kanata keyboard remapper configuration and how to make it AutoStart

## my config :
| key | onClick | onHold |
|-----|---------|----------|
|;      |   ;    |  ctrl |
|tab    |  tab   |  ctrl |
| '     |   '    |  shift |
|caps   |   esc  |  shift |
|alt-gr |   caps-lock |  caps-lock |
|backspace |   backspace |  backspace |



## to start automatically :

1. create a short cut to this path :

	```C:\Windows\System32\conhost.exe --headless the/path/kanata.exe --cfg the/path/kanata.kbd```



2. and put it in the startup folder :

	```%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup```


_Thanks to this guy on GitHub_ :
https://github.com/jtroo/kanata/discussions/193#discussioncomment-5276656