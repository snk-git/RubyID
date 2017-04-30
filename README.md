# RubyID
This software is designed to compensate for a lack of reliability of traditional passwords, it generates a password of the desired size (minimum 2048 bits) via a part of the RSA algorithm.
The software does not require installation, just put it on a USB stick and it takes care of the rest.
Whenever you need your password, your USB key will generate a Key.txt file in plain text ie unencrypted,
you will then have 30 seconds to open it and copy the password before this file is irreversibly deleted.
The rest of the time, the password is stored in an encrypted crypt.txt file, so your password never appears in clear without you asking for it.
