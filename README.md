# M95-GSM-with-REST
M95 GPRS Lib for interfacing with microcontroller.
You can use this lib with any controller just you need to map uart tx function and put some code in 
your uart rx isr and 1ms timer is required.

This lib will automatically enable gprs and check internet status .
User can provide to which site he need to update via rest call lib will open tcp connection and automatically post it.

Comments and improvemets about lib are welcome.
