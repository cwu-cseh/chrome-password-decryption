# Chrome Password Decryption

> Decrypt chrome passwords on Windows

# Notes:
> Have to be login to the Windows user who encrypted the login file (Because of CryptUnprotectData function: 
> https://docs.microsoft.com/en-us/windows/win32/api/dpapi/nf-dpapi-cryptunprotectdata)
> Input the file path for the login file.

## Usage

```shell
# Run the program
python3 run get_password.py
# Save to .txt
get_password.exe > your_file_name.txt
(The prompt won't show up, just paste the file path it and press enter twice
it will print all passwords in the text file)
```

