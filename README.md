# 3D-Mapping-and-Navigation-Bot-using-SLAM-Techniques
This project was made as part of a final year Engineering project. 

The project aims to built a prototype of a mobile robot which can be manually controlled by the user to traverse an unknown environmrnt and generate a 3D map of the surroundings.

The bot houses a smartphone which acts as the CPU of the bot
The on-board circutry consists of Node MCU wifi module, Dual H Bridge motor driver, 2000mAH Battery, Motors and Wheels
The application running on the smartphone is built using Unity Platform and Vuforia
The app uses Google's AR Core SDK and Depth API to detect surfaces and generate 3D map
This information is then rendered to the client side Unity application running on the user PC via wifi channel
The user can control and maneuver the bot with the help of live RGB image feed from the bot.
Once the survellience is done the 3D map is then rendered on the user side Unity application which can then be used for various pruposes.
