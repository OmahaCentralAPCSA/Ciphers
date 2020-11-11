# Ciphers
Exploring Caesar and Vigenere Ciphers

## Program 1: Caesar Cipher

### `Main Method`
1. Ask the user if they wish to encrypt or decrypt
2. Get the user's shift or key
3. Create a `CaesarCipher` object and use its methods. 

### `public String encrypt(String message, int shift)`  
4. Encrypts the user's message in a separate message that:  
    - recieves a message to be encrypted 
    - recieves the shift of the message
    - prints the encrypted message

### `public String decrypt(String message, int shift)`  
5. Decrypts the user's message:
    - recieves the message to be decrypted 
    - receives the shift of the message
    - prints the decrypted message
    
HINTS: 
```
int x = 65;
char y = (char)x; 
System.out.println(y); //Prints A (lower case a = 97 in ASCII)
```  
Look up the ASCII Chart  
Pick Upper Case or Lower Case  
Keep Spaces and shift numbers (handle numbers)   
There are 26 letters in the alphabet   
The modulus cycles back so, (ANY NUMBER) % 26 = (ANY NUMBER BETWEEN 0-25)


## Program 2: Vigenere Cipher

### `Main Method`
5. Ask the user if they wish to encrypt or decrypt.  
6. Gets the user's key WORD.  
7. Create a VigenereCipher object and use it’s methods below  

### `public String encrypt(String message, String key)`  
8.Encrypts the user’s message in a separate method that:
    - Receives the message to be encrypted  
    - Receives the shift of the message for every letter in the Key  
    - Prints the encrypted message
    
### `public String decrypt(String message, String key)`  
9. Decrypts the user's message  
    - Receives the message to be decrypted   
    - Receives the shift of the message for every letter in the Key  
    - Prints the decrypted message
    
Notice how similar this is to the Caesar Cipher? It’s because it is. The Vigenère Cipher is just many Caesar Shifts.
