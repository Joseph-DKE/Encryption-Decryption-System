# Encryption-Decryption-System
To encrypt any text-based message.

Took 3 hours to complete the first stage. 
Took a total of 2 days to complete the project.
You can use this to encrypt any text based message. 
The decryption system is also within the same program.

You cannot use spaces in this program though.
So instead of Hello there beautiful lady, it'll be HelloThereBeautifulLady.

The fault comes from the decryption system.
It works on the basis of groups of four but spacebar encrypted becomes BF3 and it messes with the decryption system.
Best not use space when encrypting your message so you can easily decrypt later.

The encryption system converts to ascii, runs a a few math operations, then converts to hex and prints the hex version in reverse.
ie: 
H - 143B
E - 1294
L - 168B
L - 168B
O - 185C
But the final (after reversal) is HELLO - B3414921B861B861C581
The decryption system reverses that process, obviously.

Decryption is actually harder than encryption... yeesh!

Update:
I have been able to implement a key systemthat stores the position of spaces and removes them from the encrypted message and is generated as a key
The when decrypting, you enter the encrypted message as well as the key.
It is incomplete as I have not yet added the implementation for the key in the decryption system.
Soon to be added.

Update:
Finally included the implementation of the key to the decryption system.
The system now works with spaces.

Does not include numbers and symbols. Only letters and spaces.
Might update to a version that accepts numbers and letters as well...
