# hash-function

## difference of encription and hashing :
encription = to encode some text and it can be decoded and retransform to the main text .
hashing = to encode a plain text but it can not turn back to plain text.

## hashing library in python :
import hashlib


## creating an instanse of sha256 hash method.
password = 'password'
alg = hashlib.new("SHA256")


## pass the raw password to the instanse and hash it.
alg.update(password.encode())


## see hashed value.
hashed_password = hashed_password.hexdigest()


## see all guaranteed hash algorithms ==> algorithms_guartanteed()
print(hashlib.algorithms_guaranteed)
