#Test Hardware

For a quick check is the hardware working and the PC can read sensor datause the following commads:

update packages list

```bash
sudo apt update
```
install rtl_433 tools

```bash
sudo apt install -y rtl-433
```

check is the RTL-SDR usb dongle is available.  Get list of usb devices.

```
lsusb
```

And look for DVB device type DVB
In my case it is 
"Bus 003 Device 002: ID 0bda:2838 Realtek Semiconductor Corp. RTL2838 DVB-T"

Run the rtl tool and wait some time to see the output

```
rtl_433
```

it will start with default values but the goal is to make sure USB dongle is recognized. And you may pich up some information in your neighbourhood
Look for line saying "Found xxxxxx Tuner"
In my case it is "Found Rafael Micro R820T tuner"

Use Ctrl-C to exit


