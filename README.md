# AES256 Local Encryption (Web Crypto API)

standalone html + modern JS + CSS to do encryption/decryption in a browser

## battle-tested and portable encryption

### to encrypt (enter password at prompt (twice), then type/paste plaintext. Enter is newline, so Ctrl-D is End-Of-File)
```sh
openssl enc -aes-256-cbc -salt -pbkdf2 -base64
```

### to decrypt (enter password at prompt, then type/paste ciphertext. Enter is newline, so Ctrl-D is End-Of-File)
```sh
openssl enc -aes-256-cbc -d -salt -pbkdf2 -base64
```

