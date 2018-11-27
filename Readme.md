# Some key features of JsonWebTokens to remenber:

> *Separated by three strings*
> header.payload.signature
> aaaaaaaaaa.bbbbbbbbbbb.cccccccccccc

## Header
> Usually consist of two partss
> The type of token and hashing algorithm

## Payload
> Contains the claims (statements about the user)
> Three types of claim
>> Public
>> Private
>> Registered

## Signature
> To make this you have to take the encoded header, the encoded payload, a secret, the algorithm specified in the header, and sign that.


