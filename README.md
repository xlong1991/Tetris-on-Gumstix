# Tetris-on-Gumstix
# It's a group project of 2 people. It's based on embeded system. 
# In the project, we write code for the tetris game using Qt library of C++, 
# user level control program for the linux kernel and Andriod app to control the game through bluetooth.
# to play our program, you have to follow several steps below:
# 1.Install the UserLevel.apk on an andriod cellphone.
# 2.Connect the Bluetooth part hardware and all foundamental part onto the Gumstix board and start the Gumstix.
# 3.Compile all things by Makefiles(Tetris and ul) and copy the two executable files into Gumstix.
# 4.Run the runme.sh and you may should run the export commands by yourself, although we add those into the runme.sh, it always can not run by the runme.sh.
# 5.Now use the cellphone bluetooth function to connect the Gumstix which named player1 and run andriod app to connect the Gumstix(just run the app).
# 6.If you see the information that cellphone is connecting to the Gumstix then run command "./ktimer &".
# 7.Finally run the command "./Tetris -qws" and enjoy the game.
