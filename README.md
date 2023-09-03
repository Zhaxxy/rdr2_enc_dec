# rdr2_enc_dec
Simple tool to encrypt and decrypt ps4 saves for Red Dead Redemption 2 and GTAV, detects if its encrypted or decrypted automatically

# Usage
```
usage: rdr2_enc_dec.py [-h] input_save output_save

Simple tool to encrypt and decrypt ps4 saves for Red Dead Redemption 2 and GTAV, detects if its encrypted or decrypted automatically

positional arguments:
  input_save   Path to the save file
  output_save  Path to write the output save

options:
  -h, --help   show this help message and exit
```

# Example
Decrypt save
```
python rdr2_enc_dec.py memory.dat output.bin
```
Encrypt save, fixing the checksums too
```
python rdr2_enc_dec.py output.bin memory.dat
```
