##script command records your keystrokes and session ans scriptreplay command replay the session

script -t 2> timing.log -a output.session #using the -t optinon sends the timing of keystokes to the timing.log and -a option sends the output to the output.session

echo hello world
echo This is a demonstration of script command
exit

#Replay the session
scriptreplay timing.log output.session


