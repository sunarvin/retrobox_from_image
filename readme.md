
How to scratch a game retrobox from a raw image and board?

There are always some old boards which are out of service and covered with a thick layer of dust.
Now you want to update them with latest kernel or make some interesting gadgets.
Here is an approach:

1. Abstract the binary of bootloader and kernel from the original image.
2. Locate the code for pinmux and analyze it.
3. Craft and debug your own .dts for uboot and kernel on the board.
4. Create a rootfs, port software such as SDL and fcuex.
5. Launch game and go.

  ![image](https://github.com/sunarvin/retrobox_from_image/blob/main/images/boot.png)
  ![image](https://github.com/sunarvin/retrobox_from_image/blob/main/images/game1.png)
  ![image](https://github.com/sunarvin/retrobox_from_image/blob/main/images/game2.png)

  ![image](https://github.com/sunarvin/retrobox_from_image/blob/main/images/1dts.gif)
  ![image](https://github.com/sunarvin/retrobox_from_image/blob/main/images/2game.gif)
