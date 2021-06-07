# Text-and-file-encryptor

Graphical User Interface Module

 This module uses Java Swing GUI to generate the user
interface through which a user selects the text file or can enter custom
text for encryption. This Graphical User Interface contains different
fields such as text area for entering custom text input and key. It also
contains buttons for encryption, decryption, home and view to view
the encrypted text and deciphered text.

Selecting existing text file/custom text:

 The user can enter custom text input and key for encryption in
the respective text boxes or he/she can select an existing text file
containing text data needed to be encrypted. Key should be given
manually by the user in the key text box. Encryption/Decryption can
be done by clicking Encryption/Decryption button respectively.

Encryption Module:

 This module takes either custom text or existing text file
containing data for encryption. We use Vigenere Cipher
Cryptographic algorithm. As Vigenere cipher algorithm is used for
both encryption and decryption, common key is shared between both
sender and receiver. It uses a simple form of polyalphabetic
substitution. The key is actually shifted to right by 1 position and
combined with the plaintext in order to obtain the cipher text. Once
the text box stating “File is Encrypted” is displayed, Text file is
encrypted successfully and stored in destination location.

Decryption Module:

 In this module encrypted file is given as input by selecting 
10
from the device. At this side encrypted text file will be extracted and
performs decryption operation on it. Once the respective key is
provided the decryption takes place i.e., reverse process of Vigenere
encryption. On successful decryption, “File Decrypted’’ dialog box
will be displayed and decrypted text file is stored in the destination
folder. Original Text file is obtained.
