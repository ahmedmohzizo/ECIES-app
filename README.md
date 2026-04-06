# ECIES-app

What is ECIES
ECIES (Elliptic Curve Integrated Encryption Scheme) is a hybrid encryption scheme that combines asymmetric (public-key) and symmetric cryptography to provide high security with efficient performance

**********
What is it do 
Key Agreement: Uses ECDH (Elliptic Curve Diffie-Hellman) to generate a shared secret between the sender and recipient.
Key Derivation Function (KDF): Transforms the shared secret into symmetric encryption and MAC keys.
Symmetric Encryption: Uses an algorithm like AES to encrypt the actual message using the derived key.
Message Authentication Code (MAC): Generates a tag (like HMAC) to ensure the message has not been tampered with.

***************
Key Benefits
Efficiency: Combines the security of public-key systems with the speed of symmetric encryption.
Smaller Keys: Provides equivalent security to RSA with much smaller key sizes (e.g., a 256-bit ECC key is comparable to a 3072-bit RSA key), reducing storage and bandwidth.
Built-in Integrity: Unlike basic RSA encryption, ECIES includes mandatory authentication to prevent chosen-ciphertext attacks
**********************************
how to use the app
 &&&&&&&&&  Frist &&&&&&&&&&&&&&&&&
use CMD to run the app java -jar ECIES.jar
first page 
<img width="2205" height="1926" alt="image" src="https://github.com/user-attachments/assets/7612f71d-0e2c-4792-aeb0-1fe3f710ee91" />
it shown Pubic Key and Private Key
Generate keys help you to change your Pubic Key and Private Key to get new one
&&&&&&&&&  second  &&&&&&&&&&&&&&&&&
if you choose Go Encrypt 
your public key will copy and now you can write your massage
donot forget to copey encrypt massage
&&&&&&&&&  third &&&&&&&&&&&&&&&&&
After you copy the massage use back then choose go decrypt
you will see your private key in top
now you can past your massage and use decrypt
Massage will show back

****************************
i will add the jar ECIES with pic 
enjoy




