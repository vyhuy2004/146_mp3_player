# 146_mp3_player
Final Project for CMPE 146

Note 1:
For SD card name reader test: Add these lines to terminal.cpp and use freertosmain.cpp as test file
   
    CMD_HANDLER_FUNC(taskTest);
    cp.addHandler(taskTest,  "task", "just testing");
