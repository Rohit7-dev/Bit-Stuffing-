# Bit-Stuffing-
Bit Stuffing in C 

Defination - Bit stuffing is the mechanism of inserting one or more non-information bits into a message to be transmitted,
to break up the message sequence, for synchronization purpose.

Purpose of Bit Stuffing

In Data Link layer, the stream of bits from the physical layer is divided into data frames. The data frames can be of fixed length or variable length.In variable - 
length framing, the size of each frame to be transmitted may be different.So, a pattern of bits is used as a delimiter to mark the end of one frame and the beginning
of the next frame. However, if the pattern occurs in the message, then mechanisms needs to be incorporated so that this situation is avoided.
