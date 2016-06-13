spwgen
======

spwgen is a secure password generator. It is used to create long and realtively easy to remember passwords. It uses an English (US) dictionary for generating the password.

`spwgen` is best used in a combination with a password storage 

For example, running spwgen with no arguments may produce the following password:

`Thirteenths actuate kathmandu feldspar#?`

The script has some other useful settings, running `spwgen -h` will list them all:
```
-h, --help            show the help message
  --length LENGTH, -l LENGTH
                        Maximum length of the password (default: no limit, 0)
  --count COUNT, -c COUNT
                        Number of words in the password (default: 4)
  --separator SEPARATOR, -s SEPARATOR
                        Separator between different words,
  --capitalize CAPITALIZE
                        Capitalize letters in the password [first, all,
                        random] (default: first)
  --no-specials         Don't insert special characters (one of ?,*,&,^,%,#,!)
                        (default=True)
  --specials-position SPECIALS_POSITION
                        Where to add special characters [front, back, random]
                        (default: back)
  --specials-count SPECIALS_COUNT
                        Number of special characters (default: 2)
  --specials-nospace SPECIALS_NOSPACE
                        Remove spaces before and after special characters
                        (default: True)
  --dictionary DICTIONARY, -d DICTIONARY
                        What dictionary file to use (default: en_US.dic).
                        Currently only Hunspell dictionary files are
                        supported.
  --num-passwords NUM_PASSWORDS, -n NUM_PASSWORDS
                        Number of passwords to generate
```

Requirements
============
`spwgen`'s only dependency is Python 2. 
