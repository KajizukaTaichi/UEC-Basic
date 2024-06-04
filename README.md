# UEC Basic
The simple and classical Basic interpreter from UEC.<br>
Because I'm student of UEC programming class, I named this interpreter "UEC Basic".

![image](https://github.com/KajizukaTaichi/UEC-Basic/assets/122075081/48772166-ddbd-459c-a6a8-a311de90e0db)

# Example code
Let's write this UEC Basic program on your REPL.
```basic
00 PRINTLN "Guess Game"
10 RAND SEED
20 LET SEED = round(SEED * 100)
30 PRINT "Please guess seed value: "
40 INPUT GUESS
50 IF int(GUESS) < SEED THEN 60 ELSE 80
60 PRINTLN "Too small!"
70 GOTO 30
80 IF int(GUESS) > SEED THEN 90 ELSE 110
90 PRINTLN "Too big!"
100 GOTO 30
110 PRINTLN "Great!"
```
