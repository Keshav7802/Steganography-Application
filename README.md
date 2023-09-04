
## Steganography Application

**Formats Supported-**

- Images
- Audio
- Text

>This is an important application especially in today's world.<br>
> We need to hide the messages rather than only encrypting them.

## Installation Instruction

```
# Your global Python installation needs to have pipenv
pip install pipenv

# Clone the repo
git clone https://github.com/Keshav7802/Steganography-Application.git

# Change directories into the project
cd Steganography

# [developer only] If you are developer you need to install dependencies for dev
pipenv install --dev

# If you're not a developer just install required dependencies like this
pipenv install

# Activate the Pipenv shell (aka tell your terminal/whatever to use dependencies from the env in this project)
pipenv shell

# Start the program
python -m main.py
```

## Steganography is not Cryptography ! :confused:

If you are getting confused between _Steganography_ & _Cryptography_. Then see this -

#### Cryptography

**If** `you = wms` **then** `Qcaapgrw gq gknmprylr` **= ?**<br>
_Can you guess the answer?_<br>
Here we have `key = -2` i.e. if we go 2 alphabets behind `y` you get
`w` and similarly if you go 2 alphabets behind `o` we get `m` and similarly 2 alphabets behind `u` gives us `s`. Therefore `you = wms`. <br>
So now you may have got the answer which is `Security is important`.
> Note: The cryptography algorithms are much advanced now.

#### Steganography

So now that you know what is cryptography so lets know what is _Steganography_.<br>
**If** `____=____` **then** `______=______` **?**<br>
_Confused ?_<br>
Here you won't be able to even sense the presence of data. Leave alone knowing what
is the data. That's why it is called hiding data in plain sight. There are some applications which
may detect the presence of hidden data. CIA obviously has it <emoji><br>
Generally at professional level the data hidden is encrypted first. So _steganography_ and _cryptography_ are not
mutually exclusive to each other.
>Knowledge fact: Jeff Bezos's mobile was hacked by hiding malicious code in a media
>file which on getting downloaded sent the host device's control to the hacker.

