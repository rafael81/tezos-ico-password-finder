# tezos-ico-password-finder for Human

#### Inspired from https://github.com/NODESPLIT/tz-brute

## Parameters:
##### Charset (0 - 5):

This is basically the characters that could be in your password, the lower the number and the less in the charset the better as it'll mean less permutations to test.

```
0| "0123456789"
1| "0123456789abcdefghijklmnopqrstuvwxyz"
2| "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz"
3| "0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz"
4| "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz!#$%&'()*+,-./:;<=>?@[\]^_`{|}~"
5| "0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz!#$%&'()*+,-./:;<=>?@[\]^_`{|}~"
```

##### Minimum (1 - ?):
This is the password length that the bruteforcer will start at, this can really help cut down on crack time by skipping the multitudes of permutations possible in lengths that you don't think your password would be.

##### Public key (e.g. tz1ABCDeF...):
This is the address you were given as your Tezos address upon contribution.

##### Email address:
This is the email address you used when you contributed. This is CASE SENSITIVE.

##### Mnemonic (e.g. apples cat radio...):
This is the mnemonic you received upon contribution, it will be within the PDF you downloaded. It's a long string of words all in lowercase separated by spaces.