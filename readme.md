PHP-JWT-API
=======
Script esempio di Test per autenticazione JWT API

Requisiti
------------

[x] Ultima versione PHP
[x] Composer (facoltativo)
[x] JWT (Firebase)

Per installare la libreria php-jwt di Firebase

```bash
composer require firebase/php-jwt
```

Può anche essere installata manualmente

Link

[x] [JWT](https://jwt.io)
[x] [Composer](https://getcomposer.org/)
[x] [Firebase php-jwt](https://github.com/firebase/php-jwt)

Esempio
-------

#### POST index.php

```json
{
    "utente":"mionomeutente",
    "password":"miapassword"
}
```

#### GET api.php

```header
"Authorization":"miotokenjwt"
```