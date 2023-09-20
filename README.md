# MFI Protocol Strings
An initiative for a crowdsourced list of `protocol strings` used by `MFI` devices (cars included).


|Vendor|Products|Protocol String| Additional Info
|---|---|---|---|
|Romotive|Romo|com.romotive.romo|https://github.com/Navideck/Romo-iOS-SDK
|VW Group|Tested on 2021 VW Touareg (potentially the same for many other MQB Volkswagen, Audi, Skoda, Seat vehicles)|com.vwag.infotainment.carplay.exlap, com.volkswagen.exlap, cz.skoda-auto.exlap|
|VW Group|Skoda Citigo|com.volkswagen.viwi, com.bluegiga.iwrap|
|Ford| Tested on 2017 Ford Mondeo. Also the same for select Toyota, Lexus, Suzuki, Daihatsu, Lincoln vehicles listed [here](https://smartdevicelink.com/faq/#what-vehicles)| com.smartdevicelink.prot29, com.smartdevicelink.prot28, com.smartdevicelink.prot27, com.smartdevicelink.prot26, com.smartdevicelink.prot25, com.smartdevicelink.prot24, com.smartdevicelink.prot23, com.smartdevicelink.prot22, com.smartdevicelink.prot21, com.smartdevicelink.prot20, com.smartdevicelink.prot19, com.smartdevicelink.prot18, com.smartdevicelink.prot17, com.smartdevicelink.prot16, com.smartdevicelink.prot15, com.smartdevicelink.prot14, com.smartdevicelink.prot13, com.smartdevicelink.prot12, com.smartdevicelink.prot11, com.smartdevicelink.prot10, com.smartdevicelink.prot9, com.smartdevicelink.prot8, com.smartdevicelink.prot7, com.smartdevicelink.prot6, com.smartdevicelink.prot5, com.smartdevicelink.prot4, com.smartdevicelink.prot3, com.smartdevicelink.prot2, com.smartdevicelink.prot1, com.smartdevicelink.prot0, com.smartdevicelink.multisession, com.ford.sync.prot0|https://smartdevicelink.com/en/guides/iOS/getting-started/sdk-configuration

## What are Protocol Strings?
A protocol string is a unique identifier that every MFI accessory has. There is no easy way to extract this information from the accessory itself or iOS.

## What is an MFI accessory?
It is a lightning (or 30-pin) device that connects to an iPhone/iPad/iPod Touch through Apple's proprietary port. It is licensed by Apple in order to be able to make use of the port. Also some Bluetooth devices (non BLE) are licensed under the MFI program.

## Why should this list exist?
### Minimize e-waste
Many MFI accessories have been abandoned from their manufacturers. One notable example which was brought back to life is [Romo](https://medium.com/@fotidim/romo-the-iphone-robot-f7027779e925). Without a companion app or support from their manufacturers many of those devices are useless and end up in the trash. Having access to the protocol string gives us the chance to breathe new life into them.

### Allow 3rd party apps
With the protocol string and enough knowledge about the communications protocol, we are able to create 3rd party apps for MFI accessories. Allowing 3rd party apps for an accessory promotes healthy competition and innovation. Functionalities that were beyond scope for the original manufacturer could be added.

## Contributions
If you are an MFI accessory vendor, a developer or a tinkerer and happen to know the protocol string of a certain MFI accessory make a pull request on this repo and add your device.
