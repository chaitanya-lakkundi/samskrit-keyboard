# Sulabha Samskrita Tankana Lekhani
# सुलभ संस्कृतटङ्कणलेखनी

## For Linux

How to use
==========

1. Open your favourite terminal.
2. Locate this(current) directory.
3.	 `./configure.sh`
4. 	 `./SSTL_32.run` or `./SSTL_64.run`
5. Now you can type anywhere in देवनागरी.
6. Press F8 to disable SSTL. Again press F8 to enable.
7. Goto the terminal and press <kbd>CTRL</kbd>+<kbd>C</kbd> to quit the application.

Tested On
=========

1. BOSS Linux 5.1  (64 bit)  (Bharat Operating System Solutions) [ https://bosslinux.in ]
2. Ubuntu 14.04    (64 bit)
3. Linux Mint 17.1 (32 bit)
4. Fedora 23       (64 bit)

How to develop
==============

1. The src folder contains all the sources required to build this program.
2. 	`gcc main.c -lX11 -lXtst`		to compile from source
3. If you find any bugs or would like to contribute then you can visit
	
 [ https://github.com/chaitanya-lakkundi/samskrit-keyboard ]

Examples:

1. mm nAm chaitanfyH / mama naama chaitanfyaH
    * __मम नाम चैतन्यः__
2. kRRidanfta ruupa mAlA / kRRidnft rUp maalaa
    * __कृदन्त रूप माला__

Please note that the character <kbd>f</kbd> is used for halanta. To type combined words a halanta needs to be added at the end of the first character.
Eg. To type **विश्वं**   --   **vishfvaM**		(notice that f is typed after sh which adds a halanta to श and makes it श् ).

### example:
###  ka / k - क
###  kaf - क्

## Full Keyboard Map (very similar to ITRANS format)

Vowels
------
| | | | | | |
 ---|---|---|---|---|---|
a|aa / A|i|ii / I|u|uu / U 
RRi / R^i|RRI / R^I|LLi / L^i|LLI / L^I
e|ai|o|au|aM|aH

Consonants
----------
| | | | | | 
---|---|---|---|---|
k|kh|g|gh|~N
ch|Ch|j|jh|~n
T|Th|D|Dh|N
t|th|d|dh|n
p|ph|b|bh|m
y|r|l|v / w
sh|Sh|s|h|L
kfSh|jf~n|

Special characters | Key combination | Description
------------------ | --------------- | -----------
Anusvara        |.n / M / .m|(dot on top of previous consonant/vowel)
Avagraha        |.a         |('S' like symbol basically to replace a after o)
Ardhachandra    |.c         |(for vowel sound as in english words 'cat' or 'talk')
Chandra-Bindu   |.N         |(chandra-bindu on top of previous letter)
Halant          |.h         |(to get half-form of the consonant - no vowel - virama)
Visarga         |H          |(visarga - looks like a colon character)
Om              |OM, AUM    |(Om symbol)


* [As shown, many codes have multiple choices, example "RRi / R^i" implies you
 can use either "RRi" or "R^i"]
 
## **धन्यवादाः**
