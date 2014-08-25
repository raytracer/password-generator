password-generator
==================

This password generator generates service passwords from a master password. The generated password is based on the full name of the creator, a master password, the service name and a counter (in case the original password is compromised). The algorithm is a simplified version of the [masterpasswordapp](http://masterpasswordapp.com/algorithm.html) and uses a different password template.

Libraries
---------

- [js-scrypt](https://github.com/tonyg/js-scrypt) - A javascript implementation of scrypt
- [forge](https://github.com/digitalbazaar/forge) - A javascript crypto library

License
-------

MIT
