password-generator
==================

This password generator generates service passwords from a master password. The generated password is based on the full name of the creator, a master password, the service name and a counter (in case the original password is compromised). The algorithm is a simplified version of the [masterpasswordapp](http://masterpasswordapp.com/algorithm.html) and uses a different password template. To prevent the UI from blocking web worker are being used.

Libraries
---------

- [js-scrypt](https://github.com/tonyg/js-scrypt) - A javascript implementation of scrypt
- [crypto-js](https://code.google.com/p/crypto-js/) - A javascript crypto library
- [zeroclipboard](http://zeroclipboard.org/) - A library that allows to access the clipboard using an invisible swf-file

License
-------

MIT
