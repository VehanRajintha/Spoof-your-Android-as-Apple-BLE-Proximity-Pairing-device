# Spoof-your-Android-as-Apple-BLE-Proximity-Pairing-devise

# Plese Follow Below Steps & Instructions To Do this Propper

First of all you need to download nRF Connected App Use below link to download it
https://www.nordicsemi.com/Products/Development-tools/nrf-connect-for-mobile

- After downloaded that apk then you need to install it.
- After opening the app and giving the relevant permission, you can see an interface like this....
  
  ![20231008_224809](20231008_224809.gif)


- Now enable Bluetooth adapter and click the Advertiser secter.
- Now click the  +  icon at the down of the right hand corner.
- Type anything for Display name section
- Now click ADD RECORD & Select Manufacturer Data.
- Put 004C to Company Identifier.
- Now you need to put PayloadCodes to Hex Data  section & Hit enter.

  Every payload code is down there, all they have to do is copy the payload code of the device they want to spoof and put it in the place called Hex Data.

1.Airpods
````
0x1e, 0xff, 0x4c, 0x00, 0x07, 0x19, 0x07, 0x02, 0x20, 0x75, 0xaa, 0x30, 0x01, 0x00, 0x00, 0x45, 0x12, 0x12, 0x12, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00
````
  

  
