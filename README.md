# Base58 Password Generator

A simple command line script that will generate a Base58 encoded password.

## Installation

You can install this package globally with:

```bash
composer global require 'stephenhill/base58-password-generator'
```

## Usage

If you Composer bin directory is in your PATH, simply run:

```bash
$ newpassword

8SUjt9MnDCpJmaefFjpL86snG9TgWSzp2jA2YxAAc2bw
```

By default, it will generate a 32bit password. You can specifiy the number of bits as a parameter:

```bash
$ newpassword 128

LvMwnZqV7URFEH6bJR9M7DF3z5WHUA7d1gF6zHdJLvyNYqAmbA6uXhYYcGwDNnP8imd5dpGYtf1Ytv479FgU2f3A9nkfEM4WANmy4KVCQPz2ygd9z5zUwoA8NKFo38iysu5iMW97QatmEQFejm2iaKywE8a7VLYKHqafKQ2iWuzz5DB
```
