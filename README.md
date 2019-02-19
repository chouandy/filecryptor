# File Cryptor

File Cryptor is a tool for encrypting, and decrypting file.

## Install

``` sh
go get -u github.com/chouandy/filecryptor
```

## Usage

The password can be ENV["SECRETS_PASSWORD"]

- Encrypt File

``` sh
filecryptor enc --file {file} --password {password}
```

- Decrypt File

``` sh
filecryptor dec --file {file} --password {password}
```
