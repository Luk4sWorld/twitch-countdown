# twitch-countdown
a timer that counts down. nothing more, nothing less

## usage
simply point an url to index.html for example as an OBS browser source.  
the string after the '#' hash sign contains the settings encoded as URI parameters.  

## configuration
current settings supported:
* font: the font family for the text (be ware of URI encoding, hash string will try to decode)
* size: the font size (a CSS compatible value like "40px")
* color: the font color (a CSS compatible value like "red" or "#88FF30")
* time: the time in seconds the timer should start at. (integer, "3600" or "600")

## example
  
`https://Luk4sWorld.github.io/twitch-countdown/index.html#font=Comic%20Sans%20MS&size=40px&color=#F0F0F0&time=600`  
