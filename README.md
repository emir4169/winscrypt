# about winscrypt
bad encryption method, just to test out my js
# the encryption idea
so, lets say that theres a file named "we-want-to-encrypt-this.txt", lets say the contents are "winscrypt is cool"
first of all we put every word on the file (seperated by space obviously) into a list, and then assign every word a few bits (it can be less than 8 cuz we use spaces to seperate words)
and then, we make two files one named "encrypted.txt" containing the encrypted version of "we-want-to-encrypt-this.txt", and another one named "winscryptworddata.wisy" (has the word definitions)
# the decryption idea
now we have "encrypted.txt" and "winscryptworddata.wisy", but how do we decode it?
ok so first of all for the decryption we put every encrypted word on the encrypted file (again, seperated by space.) into a list, now we look at "winscryptwordata.wisy" to get the definitions to decrypt it by just pairing the definitions with the words in the list

# is there any reason to use this over AES
2 negative reasons:
its kinda insecure
it cant run on a NES

# why are you making this
its a small challenge
