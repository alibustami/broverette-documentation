## Hardware Requirements

* Yahboom Ackerman steering chassis [link](https://category.yahboom.net/products/ros-chassis?variant=44178907070780)
* Raspberry Pi 4 Model B
* SD Card (32GB or more)
* USB Camera
* LiDAR TBA
* STM 32F4 Discovery Board
* 52Pi Ultra Thin Ice Tower Cooler Cooling Fan for Raspberry Pi 4 Model B CPU Fan [link](https://52pi.com/collections/ice-tower-cooler-1/products/52pi-ultra-thin-ice-tower-cooler-cooling-fan-for-raspberry-pi-4-model-b-cpu-fan)
* OLED Display
* 4 x female-female jumper wires
* LiPo Battery with Tplug connector 

![Parts](assets/0_all.jpg)


> Find all the necessary parts in [this Amazon list](https://www.amazon.com/hz/wishlist/ls/1HPBW0ZJIIN79)

## Step 1: Raspberry Pi and STM

Parts needed for this step:
![Parts need in step 1](assets/1_parts_needed.jpg)

start by putting the stickers for heat sinks on the Raspberry Pi 4.

| Parts Needed |  |
|---------|---------|
| ![Alt Text 1](assets/1_1.jpg) | ![Alt Text 2](assets/1_2.jpg) |

Attach the heat sinks to the Raspberry Pi 4.


|  |  |  |  |
|---------|---------|---------|---------|
| ![Alt Text 1](assets/1_3.jpg) | ![Alt Text 2](assets/1_4.jpg) | ![Alt Text 3](assets/1_5.jpg) | ![Alt Text 4](assets/1_6.jpg) |

Using these parts:

|  |  |  |
|---------|---------|----------|
| ![Alt Text 1](assets/1_7.jpg) | ![Alt Text 2](assets/1_8.jpg) | ![Alt Text 3](assets/1_9.jpg) |

Skrew the Heat sink to the Raspberry Pi 4:

|  |  |  |
|---------|---------|----------|
| ![Alt Text 1](assets/1_10.jpg) | ![Alt Text 2](assets/1_11.jpg) | ![Alt Text 3](assets/1_12.jpg) |

Add 4 x spacers to the raspberry pi 4:

| Spacers |  |  |
|---------|---------|----------|
| ![Alt Text 1](assets/1_13.jpg) | ![Alt Text 2](assets/1_14.jpg) | ![Alt Text 3](assets/1_15.jpg) |

Connect the 4 x jumper wires to the GPIO pins on the Raspberry Pi 4:

| Jumper Wires |  |  |
|---------|---------|----------|
| ![Alt Text 1](assets/1_16.jpg) | ![Alt Text 2](assets/1_17.jpg) | ![Alt Text 3](assets/1_18.jpg) |

Wires pins ([pinout ref](https://learn.sparkfun.com/tutorials/raspberry-gpio/gpio-pinout)):

* red -> 5V (pin 1)
* black -> GND (pin 9)
* brown -> SDA (pin 3)
* white -> SCL (pin 5)

Place the STM 32F4 Discovery Board on top of the Raspberry Pi 4:

![Alt Text 1](assets/1_19.jpg)

Then screw the STM 32F4 Discovery Board to the Raspberry Pi 4:

| Parts Needed |  |
|---------|---------|
| ![Alt Text 1](assets/1_20.jpg) | ![Alt Text 2](assets/1_21.jpg) |

Finally mount the Raspberry Pi 4 and STM 32F4 Discovery Board to the chassis:

| Parts Needed |  |
|---------|---------|
| ![Alt Text 1](assets/1_22.jpg) | ![Alt Text 2](assets/1_23.jpg) |

The final result should look like this:

![Alt Text 1](assets/1_24.jpg)

## Step 2: Chassis Assembly

Parts needed for this step:

![Parts need in step 2](assets/2_parts_needed.jpg)

Add 2 x spacers to the chassis base:

| Parts Needed |  |
|---------|---------|
| ![Alt Text 1](assets/2_1.jpg) | ![Alt Text 2](assets/2_2.jpg) |

Add 2 x spacers to the black plate:

| Parts Needed |  |
|---------|---------|
| ![Alt Text 1](assets/2_3.jpg) | ![Alt Text 2](assets/2_4.jpg) |

Place the black plate on top of the chassis base:

![Alt Text 1](assets/2_5.jpg)

Using 4 x screws and 4 x washers, attach the black plate to the chassis base (from front to back):

| Parts Needed |  |  |
|---------|---------|---------|
| ![Alt Text 1](assets/2_6.jpg) | ![Alt Text 2](assets/2_8.jpg) | ![Alt Text 3](assets/2_9.jpg) |

Finally, attach the top plate to the black plate using 4 x screws and 4 x washers:

| Parts Needed |  |  |
|---------|---------|---------|
| ![Alt Text 1](assets/2_10.jpg) | ![Alt Text 2](assets/2_12.jpg) | ![Alt Text 3](assets/2_13.jpg) |

## Step 3: Wiring

### 3.1 Motor Wiring
Pass the servo cable through the holes and connect it to the STM Board:

|  |  |
|---------|---------|
| ![Alt Text 1](assets/3_1.jpg) | ![Alt Text 2](assets/3_2.jpg) |

Connect the Raspberry Pi 4 with the STM Board (for power):

|  |  |
|---------|---------|
| ![Alt Text 1](assets/3_3.jpg) | ![Alt Text 2](assets/3_4.jpg) |


Connect the Raspberry Pi 4 with the STM Board (for communication):

|  |  |
|---------|---------|
| ![Alt Text 1](assets/3_5.jpg) | ![Alt Text 2](assets/3_6.jpg) |

Pass the motor cables through the holes and connect them to the STM Board:

|  |  |  |
|---------|---------|---------|
| ![Alt Text 1](assets/3_7.jpg) | ![Alt Text 2](assets/3_8.jpg) | ![Alt Text 3](assets/3_9.jpg) |

> ⚠️ Right motor -> Motor 4, Left motor -> Motor 2

### 3.2 LiDAR Wiring

Place the LiDAR on the Black Plate without mounting it and pass the cable through the holes:

| Parted Needed |  | |
|---------|---------|---------|
| ![Alt Text 1](assets/3_10.jpg) | ![Alt Text 2](assets/3_11.jpg) | ![Alt Text 3](assets/3_12.jpg) |


### 3.3 Camera Wiring

Place the camera on the top plate and pass the cable through the holes:

![Alt Text 1](assets/3_13.jpg)

## Step 4: Camera, LiDAR, and OLED Display Mounting

Cut the double-sided tape into pieces:

| Parts Needed |  |
|---------|---------|
| ![Alt Text 1](assets/4_1.jpg) | ![Alt Text 2](assets/4_2.jpg) |

Mount the LiDAR on the black plate:

| Parts Needed |  | |
|---------|---------|---------|
| ![Alt Text 1](assets/4_3.jpg) | ![Alt Text 2](assets/4_4.jpg) | ![Alt Text 3](assets/4_5.jpg) |

> ⚠️ Make sure the LiDAR is facing forward and the front edge is aligned as shown in the image.
> 
> |  |  |
> |---------|---------|
> | ![Alt Text 1](assets/4_6.jpg) | ![Alt Text 2](assets/4_7.jpg) |

Mount the camera on the top plate:

|  |  |  |
|---------|----------|---------|
| ![Alt Text 1](assets/4_8.jpg) | ![Alt Text 2](assets/4_9.jpg) | ![Alt Text 3](assets/4_10.jpg) |


> ⚠️ Insure that the camera lens is at the center axis of the robot.
> 
> ![Alt Text 1](assets/4_11.jpg)

Connect the OLED Display to the Raspberry Pi 4:

![Alt Text 1](assets/4_12.jpg)

Finally, mount the OLED Display on the top plate:

|  |  |
|---------|---------|
| ![Alt Text 1](assets/4_13.jpg) | ![Alt Text 2](assets/4_14.jpg) |