# Qmatic-Expressia-Device-Config-Chart

## A binary configuration Chart for Qmatic Expressia Feedback Devices (Open within Excel/Spreadsheet Application)

### The Chart is pretty self explanatory but there is one thing you need to keep in mind

### *The value of the Counter 1 for your organization might not be the same as the one depicted in this (which is 50)*

##### The key thing is that You take your own Counter 1 device as a reference, determine its value and then subtract 1 from it

##### That becomes the Base value and then you can add the Counter number to the Base value to get the configuration for the required counter

##### For Example:

#### In this Chart the Counter 1 has the total value = 50 (That is [0 + 2 + 0 + 0 + 16 + 32 + 0 + 0])

<a href="https://ibb.co/7yqVvJk"><img src="https://i.ibb.co/2KTPq7Z/Reference.png" alt="Reference" border="0"></a>

#### This means the Pins 2, 5, and 6 need to be turned "ON/UP" while others need to be "OFF/DOWN" (0 + 1 + 0 + 0 + 1 + 1 + 0 + 0)
 
<a href="https://imgbb.com/"><img src="https://i.ibb.co/xLrf9Kn/Legend.png" alt="Legend" border="0"></a>

##### Formula:- 

            Base value = Counter 1 - 1
            Base value = 50 - 1 = 49
            
            Base value + Counter No = Required Binary Value (for that Counter No)

#### So let's say I want the Binary value for Counter 51 and my base value is 49 ( 50 - 1 )

##### We get: 

            49 + 2 = 51 (In binary [1 + 2 + 0 + 0 + 16 + 32 + 0 + 0])
            
            Corresponding Pins are turned "ON/UP" (1 + 1 + 0 + 0 + 1 + 1 + 0 + 0)     

<a href="https://ibb.co/7yqVvJk"><img src="https://i.ibb.co/2KTPq7Z/Reference.png" alt="Reference" border="0"></a>
            
#### Now the Device will work at Counter 51

### Any Device for a corresponding counter# can be set up this way
