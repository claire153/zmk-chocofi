## How to update the keyboard configuration

- Push the updates to the git repository. 
- Wait for the "Build ZMK firmware" action to run.
- Go to the action's artifacts and download the "firmware" one.
- Flash the firmware:
  - Connect the left keyboard by USB (turned off).
  - Double click on its reset button (it's located next to the battery connector). The controller should appear in the OS as a new USB storage device.
  - Copy the correct UF2 file to the root of the controller (drag and drop works). It will automatically flash and unmount the controller.
  - Do the same with the right keyboard.
- To connect both halves after flashing them, turn them on and long click on their reset button at the same time.
