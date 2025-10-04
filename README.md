# Lowkey Screensaver
Animated webpage based on Loki (2021) TV Show intro sequence.
![Demonstration](https://raw.githubusercontent.com/Qronikarz/LowkeyScreensaver/main/demo.gif "supposed result of running the page")

Loki intro (not official upload) - https://www.youtube.com/watch?v=3QdLGiW4joY

# Configuration (permanent)
1. Text
2. Letters size
3. Fonts
4. Timer
5. Mode
6. Seconds in clock

1 - Replace the "LOWKEY" in "text_holder" variable. If there are too many letters you will need to change the text size.

2 - Change the number of vw next to the "font-size" in "#letters_place" css id

3 - To add new fonts make sure that your browser can see them and then add their names to the "installed_fonts" array

4 - Change the number in "timer" variable (units are ms whic means 1000 = 1 second)

5 - There are 2 modes now - "text" and "clock". Clock should be using your browser's time

6 - By default seconds of the clock are not displayed. Change it to "true" to allow them to appear

# Temporal configuration
You can use url parameters to change just one instance of the wallpaper:

1. text = text
2. letters size = lettersize
4. timer = timer
5. mode = displaymode
6. seconds in clock = clockseconds

Values entered for those parameters should be the same as above.

Examples of correct links:

`lowkey.html?text=LOKI&timer=450&lettersize=25vw`

`lowkey.html?displaymode=clock&clockseconds=true`

# Future updates
It may get updated with SVG filters to add grain/noise and visual tears/artifacts as seen in Loki TV intro.

# License and contributions
MIT license. No contributions will be accepted.
