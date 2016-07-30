# Assembling the weather station control unit

## Mounting the Raspberry Pi

1.  To assemble the weather station, you'll first need to mount the
    Raspberry Pi onto an acrylic base. You'll need the following
    components and kit (see Appendix 1 for contents of bags):

    1.  Large acrylic base
    1.  Raspberry Pi 2
    1.  Weather Station HAT
    1.  CR1225 coin cell battery
    1.  40-pin GPIO extender
    1.  4 x 8mm screws
    1.  4 x 6mm screws
    1.  4 x hex spacers

    ![](file:images/Mounting_Kit.jpg)

1.  Place the Raspberry Pi onto the acrylic base plate, as shown below.
    The power connector on the Raspberry Pi should be orientated to
    match the cut-out in the acrylic base:

    ![](images/Orientated_Pi.jpg)

1.  Feed an 8mm screw through the underside of the acrylic base and the
    Raspberry Pi, and secure with a hex spacer:

    ![](images/Secure_Pi.jpg)

1.  Repeat this step for the remaining screws and spacers:

    ![](images/Secured_Pi.jpg)

1.  Attach the 40-pin extender to the Raspberry Pi:

    ![](images/Attach_Extender.jpg)
    
    **IMPORTANT:** If the pins on your extender are longer and thinner than those shown in the picture, see the note in step 9.  

1.  Take the Weather Station HAT and carefully snap it in two, along one
    of the scored lines:

    ![](images/Snap_WSH1.jpg)

1.  Use pliers to remove the remaining section of the HAT:

    ![](images/Snap_WSH2.jpg) ![](images/Two_Halves.jpg)

1.  Insert the coin cell battery into the HAT, with the positive side facing upwards:

    ![](images/Coin_Cell.jpg)

1.  Attach the HAT to the Raspberry Pi:

    ![](images/Attach_Hat.jpg)
    
    **IMPORTANT:** IF the pins on the extender poke out of the top of the HAT, it is recommended that you ensure proper contact by bending the pins gently outward on each side, away from the centre. Please see the advice on our [forums](https://www.raspberrypi.org/forums/viewtopic.php?f=112&t=149912&p=985419#p985419) for futher information.

1.  Secure the hat using the 6mm screws:

    ![](images/Secure_Hat.jpg)

    You can connect a keyboard, monitor, mouse and power at this point, and proceed to installing and configuring software, then return to this guide later when you're ready to finish assembling the weather station. Alternatively, you can continue working through this guide and proceed to the software setup at a later time.

## Providing power and network connectivity

1.  The HAT provides power to the Raspberry Pi via the GPIO pins. To
    power the Raspberry Pi, you will need the following parts:

    1.  Power over Ethernet (PoE) injector
    1.  Power over Ethernet (PoE) splitter
    1.  24V transformer with international adapters
    1.  A Cat 5 Ethernet cable, long enough to reach the area you wish to place
        the weather station. (**Not supplied: see the Ethernet cable grommet section below.**)

    ![](images/Power_Kit.jpg)

1.  Connect your keyboard, screen and mouse to your Raspberry Pi:

    ![](images/KVM.jpg)

1.  Connect the PoE splitter to the Pi and the HAT:

    ![](images/Splitter_Power.jpg) ![](images/Splitter_Eth.jpg)

1.  Connect the PoE splitter to the PoE injector, using the Cat 5 Ethernet
    cable:

    ![](images/Connect_Splitter.jpg)

1.  Connect the PoE injector to the transformer, with the appropriate adapter attached:

    ![](images/Power_Splitter.jpg)

1.  Plug in the power adapter and Ethernet cable to check that the Pi is
    receiving power and connectivity:

    ![](images/Powered_Station.jpg)

## Connecting the sensors

The HAT has many sensors on the board, and several external sensors
which connect to it. More details on each sensor and how they work can be
found on the following pages: [Rain gauge](rain-gauge.md), [Anemometer](anemometer.md), [Wind vane](wind-vane.md) and [Temperature probe](temp-probe.md).

1.  There are three inputs on the Weather Station HAT, as shown in the
    image below.

    1.  The rain gauge will be plugged directly into the uppermost RJ11
        socket.
    1.  The anemometer/wind vane will be plugged directly into the
        middle RJ11 socket.
    1.  The air sensor needs assembling, as detailed below.

## Setting up the air sensor housing

For this you will need:

-     4 x plastic fixing screws
-     4 x plastic spacers
-     4 x plastic fixing nuts
-     small acrylic base
-     small air sensor housing
-     2 x mounting screws


![](images/Air_Kit.jpg)

1.  Align the air sensor board with the acrylic base as shown:

    ![](images/Align_Air.jpg)

1.  Using the plastic spacers to keep the board away from the acrylic
    base, fix it in place using the fixing screws and nuts:

    ![](images/Secure_Air.jpg)

1.  Mount the acrylic base into the housing, as shown below:

    ![](images/Mount_Air.jpg)

1.  Remove two rubber seals, opposite the RJ11 sockets:

    ![](images/Remove_Plugs.jpg)

1.  Connect an RJ11 cable and the temperature probe to the air sensor
    module, as shown below:

    ![](images/Connect_Air.jpg)


**IMPORTANT:** Do not replace the rubber seals or try to seal the cables. The air sensor housing needs to be open to the elements and this is why it's in a separate box.


## Assembling the control unit housing


For this stage, you will need:

- The large case
- 6 x 10mm screws
- Your acrylic mounted Raspberry Pi and Weather Station HAT

![](images/Housing_Kit.jpg)

1.  Unpack the large grey case, remove the 4 screws from inside and set them to one side. They are used for securing the lid at the end.

    ![](images/Main_Housing.jpg)

1.  Fix the acrylic base to the bottom of the case, using the 6 x 10mm screws:

    ![](images/Fix_Base.jpg)


## Water-proofing the control unit connections


1.  Now you can attach the rain gauge. Remove the rubber seal from the side of the case:

    ![](images/Remove_Seal.jpg)

1.  Remove the 12mm plastic nut from the grommet on the rain gauge RJ11 cable:

    ![](images/Remove_Nut.jpg)

1.  Using the nut as a guide, mark the seal with a 10mm (approx) circle:

    ![](images/Draw_Circle.jpg) ![](images/Complete_Circle.jpg)

1.  Use a scalpel or sharp knife to cut a hole through the seal:

    ![](images/Cut_Circle.jpg)

1.  Push the end of the RJ11 cable through the seal:

    ![](images/Push_Through.jpg)

1.  Push the threaded end of the grommet through the seal. Twisting might make this easier.

    ![](images/Twisting_Through.jpg)

1.  Feed the plastic nut back onto the RJ11 cable and thread it onto the grommet:

    ![](images/Plastic_Nut.jpg)

1.  Push the seal back into the case:

    ![](images/Fit_Seal.jpg)

1.  Repeat the previous steps for the wind vane.

1.  Connect the RJ11 cables to the Weather HAT:

    ![](images/Attach_RJ11.jpg)

1.  Tighten the outer end of the grommet so it grips the cable and forms a watertight seal.

![](images/Fix_Grommit.jpg)

## Air sensor grommet

Connect and seal the air sensor grommet, as per the rain sensor instructions above.

## Ethernet cable grommet

The Ethernet (network) cable has been deliberately left out of the kit, because we don't know how and where you will site your weather station: it may be close to a router or it may be 50 metres away. There are two options for networking and sealing the weather station box: either use a ready-made Ethernet cable, known as a *patch cable*, or make your own.

### Making your own network cable

If you are able to make up your own network cable, or can get someone to do it for you, then this is the best route. You can thread the smaller 16mm connector onto the cable before you crimp the network connector onto it. This way, you'll get the best seal and the length will also be perfect.

### Using a patch cable

The plastic connector of a patch cable is too big to go through the 16mm plastic sealing nut, as fitted to the rain and wind sensors. You will therefore have to use the larger 20mm sealing nut, or 'gland' as they are sometimes called. The size is marked "M20" on the collar. 

![](\images\gland.jpg) 

We tested a lot of cables and they all fitted through the 20mm connector with a bit of fiddling. You'll have to take the gland apart first, as in the picture. In one case, we had to trim the plastic of the network connector slightly with a knife. 

The downside is that the 20mm connector is too big to seal the cable properly. You'll need to seal it as best you can with tape, rubber grommets or ingenuity to keep the elements out. 

## Connecting the weather station to your network

After testing and installing your weather station, it will need to be connected to your network. This is one area where it's very hard to give specific instructions, as every school, organisation and home is different. As well as physical differences in how a computer connects, there are potential issues with firewalls, proxies, and other restrictions. Our advice is:

- If you have a network/ICT technician at your school, please get them involved in the project. 
- If you don't have a technician, find out who is responsible for your network and get them involved in the project.
- If you have questions or are stuck, then visit our [Weather Station forum](https://www.raspberrypi.org/forums/viewforum.php?f=112).

Of course, if you *are* the ICT technician or network manager, then we would love you to share your experience and knowledge on [the forums](https://www.raspberrypi.org/forums/viewforum.php?f=112).

## Finally...

We made the weather station as an educational *kit* on purpose, so that teachers and students could explore computing, sensors, networking, databases and, of course, problem solving.

If you get stuck or just want to share your experiences, [please come to the forums](https://www.raspberrypi.org/forums/viewforum.php?f=112) for a chat. Good luck and have fun!

# Next steps

Set up the [software](software-setup.md).


## Appendix 1: parts list

The contents of the plastic bags in the free weather station kit are as follows:

**Board mounting kit packet**
- Plastic fixing nuts, 4
- Plastic PCB spacers, 4
- Plastic fixing screws, 4
- CR1225 button battery
- 6mm steel screws, 4
- Receptacle (GPIO pin extender)
- Hex spacer, 4

**Enclosure kit packet**
- 10mm screws 8
- Sealing gland, M20mm x 1.5, 2
- Gland, M16x1.5, 1
- Sealing bushing (large), 2
- 25mm sealing bushing, 2

**External fixing kit packet**
- Brackets with screws, plastic, 4
- Screw covers
- Rubber washers, 4
- Self-tapping screws, 10

