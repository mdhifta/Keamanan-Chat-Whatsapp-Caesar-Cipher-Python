# Caesar Cipher
I took the reference from the notes on the medium entitled "Implementation of Caesar's Cryptography in Python" written by Ravi Dharmawan. Then I thought, "It would be interesting if I could secure my WhatsApp chat data." then I made this "WhatsApp Chat Data Security using Caesar Cipher".

Caesar cipher itself is a very simple security method, which shifts the alphabet according to a specified key.

example :
we have key: 2
Alphabet : AH
Then, A -> C (A + 2), H -> K (H + 2)

while decryption only shifts backwards, C -> A (C-2), K -> H (K-2)

if you want to run this code, there are a few things you have to prepare:

* Python 3.*
* Jupyter Notebook -> https://jupyter.org/install
* import string
* Your Chat Whatsapp txt
