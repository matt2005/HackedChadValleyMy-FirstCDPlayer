# HackedChadValleyMy-FirstCDPlayer
Hacked Chad Valley My First CD Player

## Background

[Chad Valley My First CD Player - Argos product: 349/8420](https://www.argos.co.uk/product/3498420)

![Product Image](teardown/product_image.png)

## Overview

### Idea

Repurpose as a Toniebox style player based on [MiczFlor/RPi-Jukebox-RFID](https://github.com/MiczFlor/RPi-Jukebox-RFID)

### Teardown

Once taken apart there is a circuit board.
![Circuit](teardown/circuit.jpg)


| Item          | Connection A | Connection B | High/Low | Notes                                          |
| ------------- | ------------ | ------------ | -------- | ---------------------------------------------- |
| Backward      | BP05         | BP22         |          |                                                |
| Stop          | BP05         | BP20         |          |                                                |
| Play          | BP05         | BP23         |          |                                                |
| Forward       | BP05         | BP21         |          |                                                |
| Temp+/-       | BP04         | BP23         |          |                                                |
| Volume+/-     | BP04         | BP20         |          |                                                |
| DEMO          | BP05         | BP26         |          |                                                |
| Guitar/Violin | BP03         | BP25         |          | Labeled as Guitar on PCB but Violin on Outside |
| Music Box     | BP03         | BP26         |          |                                                |
| Piano         | BP03         | BP23         |          |                                                |
| LED           | BP03         | BP04         |          |                                                |
| CD Tray       | VSS          | S01/BP14     |          | Separate PCB on CD Tray                        |
| CD Tray       | VSS          | S02/BP15     |          | Separate PCB on CD Tray                        |


| Point | Notes                |
| ----- | -------------------- |
| VSS   | Used by CD Tray      |
| BP03  | VSS?                 |
| BP04  | Active when playing? |
| BP05  | VSS?                 |
| BP14  |                      |
| BP15  |                      |
| BP20  |                      |
| BP21  |                      |
| BP22  |                      |
| BP23  |                      |
| BP25  |                      |
| BP26  |                      |