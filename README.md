**Dissclamer** 

It is a Vencore QuickCSS

It was made by (name from Discord) vending.machine on Discord and change by me

If you are in the Vencore(libVencore) Discord server hier is the Link

https://discord.com/channels/1015060230222131221/1028106818368589824/1044717748778971157

![I_need_space](https://github.com/user-attachments/assets/f5076b88-4f75-44a4-84da-ad1146fd400d)


Image was made by (name from Github) adryd325 and change by me

here is the original image

https://github.com/adryd325/oneko.js/blob/main/oneko.gif
		              
![I_need_space](https://github.com/user-attachments/assets/01895ae8-bc3e-4c10-8561-20ad18b545b6)

![I_need_space](https://github.com/user-attachments/assets/01895ae8-bc3e-4c10-8561-20ad18b545b6)
	               

		               
               
		
                
This is how my version looks like

![2025-06-18 19_11_29-#clips-und-highlights _ Server von GoldRush - Discord](https://github.com/user-attachments/assets/47a72ecf-e2dd-43b9-93f4-20b1696554b6)

This is the code if you want it too

```CSS
[class^="channelTextArea"]::after {
    content: "";
    width: 32px;
    height: 32px;
    bottom: calc(100% - 3px); /* Mess with the - 3px to change its vertical position */
    right: 0px; /* Switch this from right to left to put it on the left side, or increase/decrease to change its position */
    position: absolute;
    image-rendering: pixelated;
    pointer-events: none;
    background-image: url("https://raw.githubusercontent.com/GoldRushReal/SleepingGR/refs/heads/main/GR.gif");
    animation: oneko 2s infinite; /* change 2s to make the animation slower/faster */
}

@keyframes oneko {
    /*
    if you open the background image in ur browser, you will see that it has way more frames
    so if you want, you could make ur own keyframes for a different animation
    the top left frame is 0 0, second top row is -32 0, second row second is -32 -32 and so on
    the ...00001% makes it so that there's no transition between the frames, so if you wanted say 3 frames, you'd do 0%, 33.3%; 33.30001%, 66.6%; 66.60001%, 100%
    */
    0%, 50% {
        background-position: -64px 0;
    }
    50.0001%, 100% {
        background-position: -64px -32px;
    }
}
```

note:
this was once on the accound ![GoldRushReal](https://github.com/GoldRushReal), but I am not using this accound anymore.
