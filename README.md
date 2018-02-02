# CryptoAlgo

Standalone Python3.* linux based binary executable based Crypto program is licensed under GNU LGPLv3 (See LICENSE). The crypto algorithm is based on Simple Elliptic Curve Cryptography algorithm made available by [py-seccure](https://github.com/bwesterb/py-seccure)

Usage:
----------

1. Download and extract the zipped file {$Crypto}
2. Follow the steps as mentioned below,

	a). cd to $Crypto/crypt/ folder
      
        $./crypt

        Command line usage as follows:
        ==============================
        ./crypt keygeneration - for generating the public key
        ./crypt encrypt - for encrypting the text
        ./crypt decrypt - for decrypting the text
  
  	b). Generate the public key
        
        $./crypt keygeneration
          
        Brought to you by Crypto Algo!!
        ==============================
    
        Please enter your private key/passphrase to generate a public key
        PassPhrase:

 
  	c). Encrypt the message (image to be encrypted must be renamed as "file.jpg" and stored in $Crypto/crypt/ folder)
    
        $./crypt encrypt
        
        Brought to you by Crypto Algo!!
        ==============================

        Enter the following details!!

        Enter the text you want to encrypt..
        
        Do you want to upload an Image(Y/N) (Pl. copy the image to be uploaded in $Crypto/crypt/ folder and rename as file.jpg)
		
        Writing the necessary info to your file
 
        Please enter the 25 Character recipient address (Or you can generate one by clicking pressing 'G')..
                
        Now you can secretly send your encrypted document in '../outFiles' directory to the concerned recipient

        Encrypted file is stored in $Crypto/outputFiles/ 
  
  	d). Decrypt the message
    
        $./crypt decrypt
        
        Brought to you by Crypto Algo!!
        ==============================
        
        Enter your private key/passphrase for decrypting the message..
        PassPhrase:
        
        Do you want to validate the signature(Y/N)..
        
        The message will not be validated !!

        Decrypting the files..

        Writing to disk..
        
        Encrypted file is stored in $Crypto/info/      
  
