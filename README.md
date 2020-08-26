# Linux-Fun-facts
Some Interesting Facts about Linux.

### 1.) Cal 9 1752
- We have 11 days missing in this month.
- Bcz of the change in calendars, the julian calendar was replaced by the gregorain calender in this month.
### 2.) If we want to listen the o/p in linux
- `espeak-ng helloo`  will speak it
- `date | espeak-ng` will speak the o/p of date command.
- or we can use
- ` festival` command.
### 3.) How to see the real time running date command in CLI.
- Ans 1.) We can use `watch` command for this. watch command will give the o/p in the interval of 2-2 seconds.
- Do `watch date` will give the running time in the interval of 2 sec .
- If we want to see running time in the interval of 1 sec. use `watch -n 1 date` .
- But this is not the correct answer because it is not running in the realtime, means if we run this command then we can't run any other command below this, we have to cole it first then we can run this.
- So the correct answer for this is :
- Ans 2.)


### 4.) 4 ways throgh which we can install any OS .
- i.) If we directly install any OS on the top of the hardware then it is called Bare-Metal.
- ii.) By using Virtualization, means installing an OS on the top of that OS.
- iii.) By using Cloud Computing we can install any OS. The most tech used is Docker.
- iv.) Or we can Dual Boot our OS.

### 5.) Difference btw CTRL+C and CTRL+Z
- `Ctrl+ C` is used to stop the program.
- `Ctrl+ Z` will put your current program in background and paused it. It will not terminate/stop the program.
- To see that your program is in background or not, `jobs` is the command that will show you that wht programs you have paused yet.
- To run that paused programs again use `fg 1`,here fg means foreground and 1 is the program number which will assigned when we pause.
-Your program run from where it stopped, means it will resume the programs.

##### So to terminate the program use `Ctrl+C` in terminal.
##### To pause the program just like if you were doing chating on google and want to pause it by CLI use `Ctrl+Z`. It will paused it and then you cant open anything in that paused firefox.

### 6.) Use of `<command> & `
-  If we use like `firefox &` then it will put your firefox in background and in running status and on the same time we can run other commands also in the same terminal.


### 7.) Use of `echo` command
- echo command bydefault gives a new line and if we dont want that new line use, `echo -n "message"` .
- echo bydefault doesn't enable escape sequences.
- To enable use `echo -e "Hello \n world"`.
- Similarly we can use ` echo -e "Hello \t jay"` or `"Hello \b jiiii"`, Here t means tab and b means backspace.
- But if we do `echo -e Hello\b` and think o/p as `Hell` then it didn.t work bcz we also need to use `-n` here.

### Use `man <command name> ` for detail of any command.(This will help you a lot.)
