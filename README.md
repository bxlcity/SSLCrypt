# SSLCrypt

![SSLCrypt](https://i.imgur.com/io7Gr0b.png)

Simple Bash Scrypt to Crypt/Decrypt String or File with OpenSSL

______________________________________________________________________________________________

## Usage :

To Crypt String : ./sslcrypt -e aes-256-ecb pass 'string'

To Derypt Sting : ./sslcrypt -d camellia-256-cbc pass 'stringcrypted'

To Crypt String in file  : ./sslcrypt -ef des-ede3-cfb password in.txt out.txt

To Derypt String in file : ./sslcrypt -df aes-128-cbc password encrypted.txt decrypted.txt

![SSLCrypt](https://i.imgur.com/k5BCEyC.png)

______________________________________________________________________________________________


## Download/Install :

cd /usr/bin/ && wget https://raw.githubusercontent.com/bxlcity/SSLCrypt/master/sslcrypt && chmod +x sslcrypt && cd


______________________________________________________________________________________________



## Dependencies :

 OpenSSL ( apt-get install openssl )

______________________________________________________________________________________________


