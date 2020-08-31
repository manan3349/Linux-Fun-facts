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

#### Network: Its just a signal; either wired or wireless or fibreoptics, depends on what kind of networking we have.
##### With use of `Mobile number Spoofing` , whatever number i have same mobile number can also use in the same time.
##### Mobile number Spoofing app for android : But dont use this its a crime.
##### Same thing we can do in our laptops, whatever ip google use we can also use that ip by spoofing.
 
### To check How many network card in the PC
- `ifconfig` will list you all network card.
- The main network card that will give you internet connectivity is always your 1st network card listed there , typically known as ethernet card.
#### IP addresses(Valid/Invalid)
- Anything which has 4 octets and have range from 0 to 255 , then it is known as valid IP.
- Eg.: 192.168.0.1 is valid.
- Or we can say that,
##### - Any Ip which is valid ,that must contains a space of 4 bytes in your memory/ram.
##### - Means, all IP's or all numbers which can consumes 4bytes are the valid IP's.
#### So Any Number that con be stored in 4 bytes, it always a Valid IP.
- Examples are: `192.168.12345` is a valid IP bcz it is of 4 bytes 1st two are devided in one bytes then last octet is of 2 bytes.
- `1245.52612` is also valid ip bcz both octets are devided in 2 bytes.
- `12345689` is also a valid ip bcz we can easily store in 4bytes.
- So technically , we have devided IPs in 4 octets so that we human can easily perform operations and is easy to us to read in readable format.

#### If you want to see that how your packet is flowing to multiple cities and countries use tools like:
- `neotrace`
- `traceroute`

#### Q.) What if we want to open multiple commandline in a single go?
- Ans: For this we have to use loops like `for` and `while` loop.
- `for ((i=1 ; i<10 ; i++))`
- `do`
- `gnome-terminal`
- `done`
- This will open 10 terminals for you.
###### What if we want to close all terminals in a single click?
- Ans: Do `ps -aux | grep terminal`.
- Select the gnome-terminal server process id bcz that is the program and if we kill that p_id then all terminal gets closed.
- Then do `kill <gnome-terminal process id> ` .


### To see all the process which are running in your system(just like task manager)
- use ` ps -aux` will give you all the running process list.
- or we can use `ps -aux | grep firefox` and by this we can easily find .
- To close the firefox by cmd we can use ` kill <process_id> ` process id means whatever id is assigned by the task manager. when we do ps -aux there we will also get process-id.
- 

#### Technically, your IP store in the RAM in Binary format as 0,1.
- Just like it will first make your 1st octet number in binary and then remove the . then same as 2,3,4 octets.
- Then we convert that 32 bit binary in again decimal and if we convert in again decimal then there were no dots and thats why we obtain a big decimal number.

### Some usefull commands:
- `bc` is a calculator in cmd.
- `gnome-terminal` : will opens you a new terminal.

