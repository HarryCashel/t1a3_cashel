## Development Log

### 13/07/20

## Weather feature

I began writing this code in cloud9 in preparation for next term.
I moved each module over to ed to test that it worked.

I initally planned for a weather feature that would pull api requests
through the request library from OpenWeather.org

I mangaged to have full functionality in the cloud9 IDE using Json and Python.
However moving it to ed I discovered the workspace must not allow communication.

I probably spent far too much time trying to get this feature to work in ed.. (at least 2 days, yikes!)
In future I will look at asking for help sooner when I get stuck like this as I feel I did waste a lot of time.
Though i did learn about the request library, API's and Json, so it was not a complete waste.


### 17/07/20

## Curses library

I was having issues closing curses display to present data. The solution I came up with was to end the curses window for some features. When entering the calendar 
feature the curses function addstr is used to print the month view. However when entering the calculator function I close the curses window, clear the terminal
and allow for the user input and display of answer.



