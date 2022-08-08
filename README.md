# NSPanel

My NSPanel project. I'm using Openhab so the solution is made with mqtt since I can't use the Home Assistant API.
Right now I just have time to upload the files that I use but the plan is put together some kind of installation instruction.

There are comments above almost every component trying to explain their purpose

Here are some simple instructions to setup your own lights so that is coresponds to your setup:

Add new light
1 add mqtt component

2 add light to either table button or ceiling button component

3 update script update_room or update_mode remember to change array number to the same as the number of lights

4 add light to both up and down button for either ceiling or table up/downs

Add new switch for room
1 add binary sensor (button on the display) triggers mqtt command

2 add mqtt component (updates button value when receiving a command)
