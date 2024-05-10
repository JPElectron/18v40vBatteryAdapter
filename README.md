# 18v40vBatteryAdapter
This page is the master compatibility list for all 18v and 40v battery adapters - scroll down to find which type of adapter is a confirmed fit for your tool.

<br>
<hr style="border: 1px; height: 1px; background: #AAAAAA;">

Begining in May 2024, some assemblies that were previously hard-wired together are now shipped with a PowerPole connector and connecting cable.  This facilitates quicker build up of on-hand inventory so only the custom length connecting cable needs to be built on demand.
The dual adapters look similar, but you should only use the 18v output version with 18v tools, and the 40v output version with 40v tools.

![How to ID dual battery adapter output voltage](https://github.com/JPElectron/18v40vBatteryAdapter/blob/main/How%20to%20ID%20dual%20battery%20adapter%20output%20voltage.jpg?raw=true)

<br>
<br>

<hr style="border: 1px; height: 1px; background: #AAAAAA;">

Confirmed DO NOT USE any adapter in....

   - RY404100 or RY404010 = Blower 730 CFM, 190 MPH Whisper Series (Brushless)
       ...this model has been observed drawing too much amperage, resulting in melted contacts

   - RYi1802BT or RYi1802B6 = 1800-Watt Portable Battery Power Station Inverter Generator
       ...because it cannot communicate with the battery pack extra pins, it does not recognize the battery at all
       ...instead get RYi818BT or RYi818BG to use your 18v batteries
          
<br>
<br>

<hr style="border: 1px; height: 1px; background: #AAAAAA;">

Dual **18v side-by-side to 40v** is verified to work in the following...<br>
(note that newer 8Ah and 12Ah batteries DO NOT fit in this adapter)
 
   - RY40407 = Blower 550 CFM, 125 MPH Whisper Series (Brushless)
   - RY40408 = Blower 525 CFM, 110 MPH
   - RY404012 = Blower 450 CFM, 120 MPH 
   - RY404013 = Blower 650 CFM, 160 MPH (Brushless)
   - RY404015 or RY404150 = Blower/Vacuum 600CFM
   - RY40002 = String Trimmer/Power Head (Expand-It)
   - RY40006 = String Trimmer/Power Head (Expand-It)
   - RY40009 = String Trimmer/Power Head (Brushless)
   - RY402011 = String Trimmer/Power Head (Brushless)
   - RY40604 = Hedge Trimmer (Brushless)
   - RY408013 = Snow Shovel
   - RY40405BTL = Vac Attack Leaf Vacuum/Mulcher

<br>
<br>

<hr style="border: 1px; height: 1px; background: #AAAAAA;">

Dual **18v side-by-side WITH SPACER to 40v** is verified to work in the following...<br>
(note the spacer is a non-removable part of the assembly, wires run through it)

   - RY40407 (with thicker 9Ah packs) = Blower 550 CFM, 125 MPH Whisper Series (Brushless)
   - RY404013 = Blower 650 CFM, 160 MPH (Brushless)
   - RY404015 or RY404150 = Blower/Vacuum 600CFM
   - RY40002 = String Trimmer/Power Head (Expand-It)
   - RY40006 = String Trimmer/Power Head (Expand-It)
   - RY40220 = String Trimmer/Power Head (Expand-It)
   - RY40009 = String Trimmer/Power Head (Brushless)
   - RY402011 = String Trimmer/Power Head (Brushless)
   - RY40604 = Hedge Trimmer (Brushless)
   - RY408013 = Snow Shovel
   - RY40405BTL = Vac Attack Leaf Vacuum/Mulcher
   - RYi300BG = 40V 300-Watt Pure Sine Wave Power Source

<br>
<br>

<hr style="border: 1px; height: 1px; background: #AAAAAA;">

Dual **18v INLINE to 40v** is verified to work in the following tools...

   - RY404013 = Blower 650 CFM, 160 MPH (Brushless)
   - RY404015 = Blower/Vacuum 600CFM (but impedes usage of the front adjustable handle)
   - RY40002 = Cordless String Trimmer
   - RY40220 = String Trimmer/Power Head (Expand-It)
   - RY408013 = Snow Shovel
   - RY40405 = Vac Attack Cordless Battery Leaf Vacuum/Mulcher
   - RYi300BG = 40V 300-Watt Pure Sine Wave Power Source
   - RY401021 = Lawn Mower 21in (but impedes closing the battery door)

<br>
<br>

<hr style="border: 1px; height: 1px; background: #AAAAAA;">

Use the dual 18v adapter in place of a Ryobi 40v battery such as those with P/N...

   - OP4015, OP4015A = 1.5Ah
   - OP40201 = 2Ah
   - OP4020A = 2Ah
   - OP4026, OP40261 = 2.6Ah
   - OP4030, OP40301 = 3Ah
   - OP4040, OP40401 = 4Ah
   - OP40404 = 4Ah
   - OP4050, OP40501 = 5Ah
   - OP40504 = 5Ah
   - OP4050A = 5Ah
   - OP40601 = 6Ah
   - OP4060A = 6Ah
   - OP4060A1 = 6Ah
   - OP40602 = 6Ah
   - OP40604 = 6Ah
   - OP40605 = 6Ah High Capacity
   - OP40752 = 7.5Ah
   - OP40754 = 7.5Ah
   - OP4080A = 8Ah
   - OP40804 = 8Ah
   - OP40125 = 12Ah
   - OP4012A1 = 12Ah

More information on 40v batteries is available from toolboy's excellent site: https://toolboyworld.com/eBay/Ryobi_40v_Batteries.htm

<br>
<br>

<hr style="border: 1px; height: 1px; background: #AAAAAA;">

Safety reminder...

Never try to charge two Ryobi Li-Ion batteries in series or parallel (this means no putting any dual adapter in a 18v or 40v charger) as damage to the internal Battery Management System (BMS) or the charger is possible. The charger cannot communicate with the battery pack extra pins to get temperature or charge current, without this info the charger may assume the wrong data and create a fire hazard, so always charge batteries individually and in approved chargers.  Genuine Ryobi chargers appear to do the right thing and not even attempt to charge, but 3rd party/aftermarket chargers may not be as smart.

I admit I am overly paranoid about charging Lithium-ion batteries: I only charge when I am at home, I only charge within the house (a temperature controlled environment) and never a garage or shed (subject to extreme heat or cold). I have the charger plugged into a z-wave smart outlet with the following logic via HomeSeer software and some custom scripts: If I ever leave (my phone un-associates from the house WiFi) the z-wave outlet will turn off power to the charger, A smoke detector is positioned directly above the charger, If the smoke detector goes into alarm then the z-wave outlet will turn off power to the charger. You too should strongly consider that charging unattended or in extreme temperatures is unnecessary risk, stay safe out there.

<br>
<br>

<hr style="border: 1px; height: 1px; background: #AAAAAA;">

[Last Updated 05-10-2024]
