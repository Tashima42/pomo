## Pomo, a simple CLI pomodoro timer

Pomo is almost the simplest possible pomodoro timer.

![image](https://user-images.githubusercontent.com/23709916/146772035-9ee0885f-9102-4d96-bc76-6d141e3702c9.png)

**Pomo will notify you when it's time for a break, or time to focus.**

### Installation

Attention: Always inspect scripts before running

````bash
curl https://raw.githubusercontent.com/Tashima42/pomo/main/install-pomo-sound.sh | bash
```

### Examples
* Start a pomodoro with 20 minutes of focus time
    ```bash
    pomo 20
    ```
* 20 minutes of focus time and 3 minutes of break time
    ```bash
    pomo 20 3
    ```
* 20 minutes of focus time, 3 minutes of break time and 10 minutes of long break
    ```bash
    pomo 20 3 10
    ```
* 20 minutes of focus time, 3 minutes of break time, 10 minutes of long break and 4 cicles of focus until long break
    ```bash
    pomo 20 3 10 4
    ```

### Usage

````

Usage: pomo [options] focus break long_break breaks_until_long
options -h: display help message
focus Minutes of focus until break | Default = 25
break Minutes of break until focus | Default = 5
long_break Minutes of long break until focus | Default = 15
breaks_until_long Number of breaks until long break | Default = 4

````

Uninstall:
```bash
rm ~/.local/bin/pomo
rm -rf ~/.config/pomo
````
