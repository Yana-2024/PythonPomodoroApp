Description:
      Desktop Pomodoro Timer Application built using the Tkinter in Python.
Features:
      *Multiple timers:* 1. Pomodoro: 25 mins work
                         2. Short Break: 5 mins break
                         3. Long Break: 15 mins break after 4 pomodoro cycles
      *Start:* Allows the user to start the timer
      *Stop:*  Allows the user to stop the current timer permanently
      *Reset:* Allows the user to reset the number of pomodoros to 0
      *Skip:*  Allows the user to skip the current timer
      *Pomodoro Counter:* counts the number of pomodoros done
Libraries Used:
      *tkinter:* for the GUI (labels, buttons, etc) 
      *time:* for controlling the time (countdown, sleep, delay)
      *threading:* used 2 threads: 1 main thread and 1 side thread to run the timer in the background. This ensures the UI remains responsive when the timer is running
