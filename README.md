Project Synopsis 
Project Title: Clock and Timer 
1.Introduction 
The “Clock and Timer” application is an Android app that includes various time-related 
utilities such as a local clock, world clock, stopwatch, countdown timer, alarm and game 
timers for Chess and Kabaddi. Unlike standard clock apps, this application brings together 
general timing tools and sport-specific timers in one place. It is designed to provide 
accurate time tracking, easy navigation, and some features that work even when the app is 
minimized. The modular design ensures each feature is clear, simple to use, and serves its 
purpose. 
2. Core Objectives 
• To provide an accurate and user-friendly local and world clock. 
• To include a stopwatch with lap recording and statistics. 
• To create a countdown timer with notifications on completion. 
• To add game timers for Chess and Kabaddi with custom settings. 
• To store and retrieve persistent data using a database where required. 
• To allow customization such as adding or removing world clocks and setting timer 
durations. 
 
3. Detailed Module Breakdown 
Module 1: Local Clock & World Clock 
Features: 
• Show Local Clock (HH: mm: ss) in real time (digital format). 
• Toggle between 12-hour / 24-hour format – Lets user choose preferred time format. 
• Add clocks from list of countries like UAE, USA, Japan, Australia and Germany. 
• Show Date and Day for each clock. 
• Show time difference in world clocks compared with local time – Indicates how many 
hours ahead/behind another time zone is. 
• Delete a clock from the list – Remove any unwanted clock except the local clock. 
• Persist user-added clocks even after app restarts – Saves clocks in local storage until 
user resets them. 
• Reset to default functionality removes all except local clock. 
 
Feature Workflow: When the app is opened, the user is shown the Local Clock screen with 
the current time. The user can add the world clock from the list of options.  
 
 
 
Module 2: Stopwatch 
Features: 
• Start, pause, and reset stopwatch functionality – Basic stopwatch operations for timing 
events. 
• Record multiple laps with timestamps for the current session – Allows user to capture 
intermediate timings without stopping the stopwatch. 
• Scrollable lap list display – Displays each lap in order with recorded time. 
• Display statistics (fastest lap, slowest lap, average lap) after reset – Displays fastest, 
slowest, and average lap time after session ends. 
 
Feature Workflow: The user can start the stopwatch, record laps, and pause or reset it. Lap 
details are shown in a scrollable list, and summary stats appear after reset. 
 
Module 3: Countdown Timer 
Features: 
• Set custom countdown durations – Allows the user to choose any countdown time. 
• Start, pause, and reset timer – Standard timer controls for flexibility. 
• Multiple preset timers – Quick-select options like 1 min, 5 min, and 10 min. 
• Notification on completion– Alerts the user when the timer reaches zero, if app is open 
and timer is visible then alert on screen else on notification if the app is minimized. 
• Pomodoro and activity beeps – Option to use the timer for focused work or physical 
activities with periodic beeps. For example, 25 minutes work -> 5 minutes break and repeat 
in cycles and optional long break after 4 pomodoro cycles. 
Feature Workflow: The user sets the desired time, starts the countdown, and is notified 
when it ends. 
 
Module 4: Alarm  
Features: 
• Set one-time alarms – Allows user to pick a specific date and time for one time alarm. 
• Custom ringtone selection – Lets the user choose from available tones or add their own 
sound. 
• Custom labels – Set custom labels for alarm. 
• Alarm rings even if app is closed – Uses Android’s alarm scheduling so it works in the 
background. 
• Snooze and dismiss options – Standard alarm controls to stop or delay ringing. 
 
Feature Workflow: The user sets an alarm for a specific time, customizes it, and confirms it. 
The alarm rings at the set time regardless of app state. 
 
 
Module 5: Game Timers 
Submodule A: Chess Timer 
• Two-player countdown timers – Separate timers for each player. 
• Custom time for each player – Allows different time limits for each timer but change 
time limits only before timer starts. 
• Move counter – Tracks number of moves made and number of moves visible on screen. 
• Switch turns manually via button press – Button click ends current player’s turn and 
starts the other’s timer. 
• Pause and reset functionality – Players can pause the timer this will pause both player 
timers and timer can be reset. 
 
Submodule B: Kabaddi Timer 
• Custom total match time – Lets user set the overall game duration. 
• Half-time auto calculation – Automatically sets the half-time break as half the total time 
and rounding off if needed. 
• Timeout support – Lets user pause the game for short breaks. 
• Pause, resume, and reset options. 
 
Feature Workflow: The user selects a game timer type (Chess or Kabaddi), sets the time, 
and starts the timer. Game-specific rules like move counting or half-time alerts are applied 
automatically. 
Module 6: Settings 
Features: 
• Change clock display format (12-hour / 24-hour). 
• Reset all app data – Clears saved clocks, alarms, laps, and settings to default. 
 
Feature Workflow: The user opens Settings from the navigation and adjusts app 
preferences. 
4. Conclusion 
The Clock and Timer application provides a combination of basic and specialized 
timekeeping tools. By including modules such as local and world clocks, stopwatch with lap 
statistics, countdown timer with notifications, one-time alarms, and game timers for Chess 
and Kabaddi, it offers both everyday utility and unique features. All features are designed to 
be user-friendly while covering a wide range of time management needs.
