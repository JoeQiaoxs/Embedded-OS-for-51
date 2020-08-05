# Embedded-OS-for-51
An embedded OS for 8051 from scratch.

1. Memory Architecture

```C
/*
	
|-00--- ---07-| |-08--- ---0f-| |-10--- ---17-| |-18--- ---1f-|	|-20--- ---2f-| |-30--- ---7f-|	|-80--- ---ff-| (iDATA)
												|-80--- ---ff-| (SFR)

|-0000--- ---1fff-| (iXDATA)
												
|-0000--- ---ffff-| (CODE)

*/
```

2. Interrupt System
