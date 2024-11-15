
[![python3](https://img.shields.io/badge/python3-v3.6-green?style=for-the-badge&logo=python)](https://www.python.org)


# NTRU_cryptography
A Post-Quantum Encryption Algorithm

This repository contains all codes related to my research paper titled "**Enhancing the NTRU Cryptosystem**". The paper is available here: https://www.ijcaonline.org/archives/volume176/number29/31388-31388-2020920320

NTRU is an open-source public key cryptosystem that uses
lattice-based cryptography to encrypt and decrypt data. Unlike
other popular public-key cryptosystems, it is resistant to
attacks using Shor's Algorithm and its performance has been
shown to be significantly greater. 

This paper talks about how
Koblitz encoding from Elliptic Curve Cryptography (ECC)
can be used to convert each character in a dataset to a point on
an elliptic curve. A sum of squares analogy is pitted against
the cantor pairing function to turn the point to a single
number, which is converted to a sequence of coefficients in Z.
A polynomial is then generated for each of these characters.
Then the polynomial is reduced, and then shown that choosing
appropriate parameters for the cryptosystem can make it
highly secure and that the decryption algorithm turns out
taking linear time. Since each character is represented by its
own polynomial, it increases obscurity thereby increasing the
complexity for decryption and thus the security level. 

A form
of data compression has also been implemented and it has
been tested whether data compression and expansion during
the encryption-decryption process results in original data with
no or minimal loss.

## Cloning
```bash
$ git clone https://github.com/Jaggiiii/crypto_project
```

## Dependencies
```bash
$ pip3 install -r requirements.txt
```

## Demonstration

![ntru_gif](https://user-images.githubusercontent.com/36446402/82535268-40895b80-9b64-11ea-81cc-0c55677fc22a.gif)

## Output

![Screenshot from 2020-02-06 12-43-24](https://user-images.githubusercontent.com/36446402/73914025-5d17c580-48de-11ea-8ae5-b07e0940b306.png)


