# first install
python -m pip install cryptography

# ECDHE
ECDHE in python
# how it works
ECDHE is aimed to ensure that data is coming from a specific source. it encrypts data using private key and decrypts it using publickey. Example: if A communicate with B, then A will encrypt data using his privateKey (prkA), and send it to B in this format: (normalMessage, SignedMessage). in the other hand B will use A's publicKey (pkA) to decrypt SignedMessage, if normalMessage == SignedMessage then the message recieved is from A.
