# Automatic-windowblinds
Automated windowblinds using ESP32, PWM driver board, two servo motors (360 and 180 degrees) and Arduino IDE as platform.
Code creates a local webserver for manual control if wifi settings are correct. For manual control, always set automation off in the webpage. Otherwise it automatically checks birghtness levels every second, rotates 360 degree servo for set amount of time if the correct brightness levels are reached and rolls it backwards if brightness decliness enough. 180 degree servo rotatess back and forth every 10 seconds (currently) if the 360 servo is on "down" position.
This was a school project, most of the integers and strings use Finnish words.
Everything should work.
