# Introduction to Number bases
###### Don Greer 2018-09-01

Imagine a bucket full of marbles.
If I told you that there were one thousand two hundred and thirty four marbles in the bucket, you would know that they could be grouped into one group of one thousand marbles, two groups of one hundred marbles, three groups of ten marbles and four single marbles. Just the way you did it in kindergarten.

Now if I had told you the number of marbles in French, how many marbles would there be then ? (hint: the number of marbles didn’t change, just the way I communicated the quantity to you changed.)

What if I had told you in Swahili or Arabic? How about if I told you in Roman numerals? `MCCXXXIV`

What if I told you the quantity of marbles in base 2 (binary) or base 8 (octal), or base 16 (hexadecimal) or even base 60? (side bar: base 60 is still a thing, consider how many minutes there are in an hour.)

In each case: The number of marbles didn’t change, just the way that I communicated that quantity to you changed.
Lets talk about some different ways to describe numerical quantities.
## BASE 10 or the Decimal system
If I told you that there were one thousand two hundred and thirty four marbles in the bucket, you would know that there were:  (The first column in the following chart is the decimal digit, it is multiplied by a power of ten because this is base ten)

| digit | multiplier | product | note | explanation |
| --- | --- | ---: | --- | --- |
| 1 | * 10^3 |  = 1000	|	one group of 1000 |	10 to the power of three is 1000
| 2 | * 10^2 | = 200 | two groups of 100 |	10 to the power of two is 100
| 3 | * 10^1 | = 30	|	three groups of 10 |	10 to the power of one is 10
|4 | * 10^0 | = 4	|	four groups of one | 10 to the power of zero is one
| | sum | 1234 |

This is way too easy: We have all been using base ten since before we started school. Humans probably developed base 10 because they started counting on their fingers and there are ten of those (if you include your thumbs).

One of the characteristics of our base 10 number system, is that there are 10 symbols used to represent numbers (the digits zero through nine). When we run out of symbols after nine, we have to start using more than one symbol to describe the quantity. More on this later.

But now lets go on a little side trip to the planet Cartoonious!

## Base 8 or Octal
This planet is named Cartoonious because the discoverers were reminded of the Saturday morning cartoons that they watched as kids. Did you ever notice that many cartoon characters only have three fingers and a thumb on each hand? Actually the real name of the planet is Octal but I think that Cartoonious is neater don’t you?

Lets think about how they count on planet Cartoonious:
When they hold up both hands and you count the number of fingers and thumbs (digits), you only get to eight. Because of this they never invented any symbols for what would be eight and nine in the decimal system. They go directly from seven to what would look like the two digit number ten to us.

Remember that this is base 8 and these symbols mean something different than what you are used to!
This is how they would count compared to its equivalent in base 10:

| base | sequence |
| --- | --- |
| base 8 |  `0, 1, 2, 3, 4, 5, 6, 7, 10, 11, 12…16, 17, 20, …` |
| base 10 | <code>0, 1, 2, 3, 4, 5, 6, 7, &nbsp;8, &nbsp;9, 10…14, 15, 16, …</code> |

When I asked them how many marbles were in the bucket: they said that there were `2322`(base 8) marbles in the bucket.
Lets convert this base 8 number to a base ten number: (The first column in the following chart is the number they gave broken down by column and because this is base eight we use powers of eight in the second column.)

| digit | multiplier | product | note | explanation |
| --- | --- | ---: | --- | --- |
| 2 | * 8^3 | = 1024 | two groups of 512	|	8 to the power of three is 512 |
| 3 | * 8^2 | = 192 | three groups of 64 |8 to the power of two is 64 |
| 2 | * 8^1 | = 16 | two groups of eight	|	8 to the power of one is 8 |
|2 | * 8^0 | = 2 | two groups of one | 8 to the power of zero
| | sum | 1234 |

So yes, `2322`(base 8) means the same as `1234`(base 10). Remember: We didn’t change the number of marbles in the bucket, just the way we described it.
But now it is time to go adventuring again!
Its time to go adventuring through space and time again. Lets visit ancient Phoenicia.

## Base 60
After reading all of this you may be wondering if the ancient Phoenicians who used base 60 had 30 fingers on each hand. This is unlikely, but perhaps they had 60 places on their body that they used for counting, Perhaps they started with the 5 toes on one foot, moved up one leg then down and back up that side’s arm, across the head, and back down the other side of their body ending with the five toes on the other foot.

Base 60 is used in time and also in longitude and latitude (recall that those are often described in terms of degrees:minutes:seconds).

The convention when printing base 60 is that instead of inventing 50 new symbols you use pairs of decimal digits with colons to separate the digit pairs – like on your digital clock. The colons group pairs of digits that must remain together because the digit pair are really one digit in base 60. This is a hybrid of decimal and base 60. It uses two symbols to form a single base 60 digit, and uses the colons to separate the symbols. We will see a similar trick when we look at dotted decimal notation.

Because of the colons you could get away with dropping the leading zero in some fields and only using a single digit (for example `12:5:30`) but the usual convention is to always print the leading zero so that you have two digits for the minutes and seconds. The leading zeros are usually dropped in a similar situation in dotted decimal notation. (coming soon)

## Base 16 or Hexadecimal
Lets take a trip to the planet Hexadecimal. It was named this because an evil witch put a spell on the people there and caused them all to have seven fingers and a thumb on each hand! When they hold up both hands and you count all of the fingers and thumbs, you get sixteen.
When you ask them how many marbles are in the bucket they answer like this

**Red Alert arm the PHASERS, we have a problem here**

Because the Hexians have sixteen fingers they have invented sixteen different symbols for the values zero through 15. I do not have any special symbols on this keyboard to translate from the Hexian symbols for what in base ten is called 10 through what in base ten is called 15.
I will have to invent some new symbols and get a special keyboard made. This will take much too long.

**OK a compromise**

I will use the letter `A` in the place were the Hexians have their special symbol for their eleventh digit through the letter `F` for the place were the Hexians write the symbol for their sixteenth digit. Please remember that these are not letters anymore, these are special number symbols as translated from the Hexian system.
So here is how they count

| base | sequence |
| --- | --- |
| HEX |	<code>0, 1, 2, 3, 4, 5, 6, 7, 8, 9, &nbsp;A, &nbsp;B, &nbsp;C, &nbsp;D, &nbsp;E, &nbsp;F, 10, 11, 12, … 1F, 20, …</code> |
| Decimal |	 `0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, … 31, 32, …` |

Remember that `A` here is the symbol for the quantity `10` (base 10) and `F` is the symbol for the quantity `15` (base 10): these are numbers not letters here. (Zero is the first digit and `F` is the sixteenth digit.)

When I asked them how many marbles were in the bucket they said that there were `04D2` marbles. Lets see how this works: (because this is base 16 we use powers of 16 in the second column)

| digit | multiplier | product | note | explanation |
| --- | --- | ---: | --- | --- |
| 0 | * 16^3 | = 0 | zero groups of 4096 | 16 to the power of three is 4096 |
| 4 | * 16^2 | = 1024 | four groups of 256 | 16 to the power of two is 256 |
| D | * 16^1 | = 208 | 13 groups of 16 | 16 to the power of one is 16 |
| 2 | * 16^0 | = 2 | two groups of one | 16 to the power of zero is one |
| | sum | 1234 |

Remember that `D` here is the special Hexadecimal symbol for the number `13` (base 10), not a letter.
So yes `04D2`(base 16) means the same as `1234`(base 10). Again: We didn’t change the number of marbles in the bucket, just the way we described it.
Note sometimes you may see colons added to a Hexadecimal string. Check the MAC address on your computer or router and you may see something like this

`52:54:00:54:d9:7a`

The colons are just there to improve readability and to help the reader keep track of the 8 bit boundaries (2 hex digits are stored as 8 bits in a computer). The colons in a base 60 number and the dots in dotted decimal do a further job, read on for more. Another way to look at it would be to call this base 256 and say that the two symbols between the colons combine for a single base 256 digit. More on a similar approach when we discuss dotted decimal notation.

Lets go adventuring again! Off to the planet Rudolphus!

## Base 2 or Binary
The planet Rudolphus is a very strange place, the Rudolphians don't have any fingers so they count with their nose. It was named after the famous Christmas reindeer and like Rudolph; they can make their nose glow. When they are counting, they leave their nose dark for a zero and light it up for a one. (Lets all take a brief break so we can all sing the Rudolphus national anthem: Rudolph the Red Nosed Reindeer).
The Rudolphians do not have any symbols for any digits other than zero and one, so they count like this:

| base | sequence |
| --- | --- |
| binary |  `0, 1, 10, 11, 100, 101` |
| Decimal | <code>0, 1, &nbsp;2, &nbsp;3, &nbsp; 4, &nbsp; 5</code> |

When I asked them how many marbles are in my bucket they answered `100 1101 0010`. (The extra spaces are put there just to improve readability, like putting commas in a big decimal number.)

How did they come up with this? Again the first column in the following chart contains the digits in the number provided by the Rudolphians and because it is base two we are using powers of two in the second column.

| digit | multiplier | product | note | explanation |
| --- | --- | ---: | --- | --- |
| 1 | * 2^10 | = 1024 | 1 groups of 1024 |2 to the power of ten is 1024 |
| 0 | * 2^9 | = 0 | 0 groups of 512 |	2 to the power of nine is 512 |
| 0 | * 2^8 | = 0 | 0 groups of 256 |	2 to the power of eight is 256 |
| |
| 1 | * 2^7 | = 128 | 1 groups of 128	| 2 to the power of seven is 128 |
| 1 | * 2^6 | = 64 | 1 groups of 64	|	2 to the power of six is 64|
| 0 | * 2^5 | = 0 | 0 groups of 32 | 2 to the power of five is 32|
| 1 | * 2^4 | = 16 | 1 groups of 16	|	2 to the power of four is 16|
| |
| 0 | * 2^3 | = 0 | 1 groups of 8	|	2 to the power of three is 8|
| 0 | * 2^2 | = 0 |0 groups of 4 | 2 to the power of two is 4 |
| 1 | * 2^1 | = 2 | 1 groups of 2	|	2 to the power of one is 2 |
| 0 | * 2^0 | = 0 | 0 groups of one | 2 to the power of zero is 1 |
| | sum  | 1234 |

So yes `100 1101 0010`(base 2) means the same as `1234`(base 10). Don’t forget: We didn’t change the number of marbles in the bucket, just the way we described it.  The extra spaces are there only to improve readability, much like adding commas to a large number in base 10.

Its time to go adventuring through space and time again. Lets look at the internet address on your computer.

## Dotted decimal notation
Here is yet another way to write numbers and it does not use letters for numbers the way I did when translating numbers from the planet Hexadecimal.

When you are working with IPv4 (Internet Protocol version 4) you are often working with 32 bit binary numbers.  for example: Internet addresses in IPv4 are values between `0` and `2^32-1` inclusive, or as the Hexians like to say:
numbers between `0` and `FF FF FF FF` (base 16).

If you look at the network IP address on your cell phone or on your desktop computer you will probably see a number something like this:

`192.168.0.100`

What is going on here?
Each of the four numbers separated by the dots can have a value between 0 and 255 inclusive. This is base 256. They are using one to three decimal digits to give the value in each position and using dots to separate the values:

| base | sequence ||||
| --- | --- | --- | --- | --- |
| 192 | * 256^3 | =   3221225472 | 192 groups of 16777216| 	256 to the power of three is 16777216 |
| 168 | * 256^2 | = 11010048 | 168 groups of 65536 |	256 to the power of two is 65536 |
| 0 | * 256^1 | = 0 | 0 groups of 256	|	256 to the power of one is 256 |
| 100 | * 256^0 | = 100 | 100 groups of one |	256 to the power of zero is one |
| | sum | 3232235620 (base 10)

Note that the dotted decimal convention allows dropping leading zeros from the individual base 256 digits unlike the usual rules for printing time in base 60.

## Base 64
If you investigate Internet mail encoding (SMTP) you may run into MIME type Base64.
If you look at https://en.wikipedia.org/wiki/Base64 you will see a table that maps the numbers `0` through `63` to sixty four different printable (ASCII) character codes This mapping is similar to what you have seen in the other number bases we have already discussed.
You may also see base64 encoding in parts of some encryption key files and certificate file types if you open the file with a text editor.
In these examples BASE64 is used to make binary data view-able in a simple text editor (for example Microsoft Notepad as opposed to Microsoft Word) or transmittable over a 7 bit data communications line like some old style serial communications lines.

## Conversions
A revisit to the planets Hexadecimal and Rudolphus and a discussion on making conversions easy.
You probably know that inside a computer everything is done in binary, but you may be wondering : so why do I have to learn Hexadecimal? Long binary numbers are not only hard on the eyes but they are error prone to type. You could use decimal in some places but when you get to bit twiddling, the positions of the bits are not obvious and the conversion is hard to do. What if there was a really easy way to convert to/from binary to hexadecimal? Consider the following table:

|Base|value ||||
|---|---:|---:|---:|---:|
| Hex | 0 | 1 | 2 | 3 |
| Binary | 0000 | 0001 | 0010 | 0011 |
||
| Hex | 4 | 5 | 6 | 7 |
| Binary | 0100 | 0101 | 0110 | 0111 |
||
| Hex | 8 | 9 | A | B |
| Binary | 1000 | 1001 | 1010 | 1011 |
||
| Hex | C | D | E | F |
| Binary | 1100 | 1101 | 1110 | 1111 |

Note that every hexadecimal character (digit) can be represented in four binary digits.
You may want to cut this table out and post it on your refrigerator (tell your mom that I said that it was OK).
Now look at these example conversions:

|Hex | Binary | Dotted decimal notation | Decimal |
| --- | --- | --- | --- |
| 04D2 | 0000 0100 1101 0010 | 0.4.13.2 | 1234 |
| C0:A8:00:64 |  1100 0000  1010 1000  0000 0000  0110 0100  |192.168.0.100 | 3232235620 |

Note that the binary value digit groups map exactly to the hex digits from the table above! Its so easy you can do it in your head as fast as you can write it down. And four hex digits is certainly easier to remember than a series of 32 ones and zeros. This is why you need to learn hexadecimal.

## Review
Do you see how easy it is to convert to/from the Hexians writing of `C0 A8 00 64` (base 16)  to the Rudolphians writing `1100 0000 1010 1000 0000 0000 0110 0100` (base 2)

Which would you rather have to remember?

Which would be easier to do binary math (on paper) with? (more on binary math later)

Can you convert between hexadecimal and binary easily?

Do you see that the conversion is much harder to/from base 10, but that conversions to/from the other three are relatively easy?

Note: the new IPv6 will use HEX instead of dotted decimal notation for network addresses (if and when it finally becomes popular).

## Using numbers written in other bases in your programs
In C and in C++ programming languages, this is how it is done:

| Source Code | Compiled |
| --- | --- |
| 1234 | The compiler will assume that this is a decimal number |
| 02322 | The leading zero indicates to the compiler that this number is octal or base 8 – watch out: it is really easy to miss the significance of the leading zero when reviewing code |
| 0x4D2 | a leading 0x indicates to the compiler that the value is in hexadecimal. The letter symbols in the number may be either upper case or lower case |
| 0b10011010010 | a leading 0b indicates to the compiler that the value is in binary |
| B10011010010 | a leading uppercase B indicates to the compiler that the value is in binary in the Arduino compiler|

### Other Compiler notes
Above I said that `1234` is the notation for a decimal value.
You will also see the notation `1234L`

The trailing `L` means that this is a long integer value – more on this when we discuss integer sizes and types.

We will also discuss the differences between Signed and Unsigned integers at that time.

You will also see numbers written with decimal points:

`1234.456`

Anything with a decimal point is either a float or a double. We’ll have more on this when we discuss floating point notation.

## Exercises for the student
### One
We did not visit the planet Twinkletoes today. It is an wonderful place: everyone goes barefoot all the time and they use a base 20 number system. How would they have written the number of marbles in our bucket?
### Two
All of the examples in this document have shown how to convert from other bases into base 10. How would you write a program to convert from base 10 into another base? Hint: you may find the C or python language remainder operator `%` useful.
### Three
Can you write a command line program that will:

1. ask the user to input a number base in base 10 (2 through 36 allowed)

1. ask the user to input a number for conversion in that base. Remember: good programmers error check all user input. The program should print an error if the user inputs a symbol not allowed in the requested base.

1. print out the input number converted to Binary, Decimal, and Hexadecimal formats.
Hint: Have a look at the printf() function in C or print() in python.

1. Can you write a new version of the program above that will start like the one above but will also ask the user to select an output base. The program will then print out the user’s input number converted to the the requested output base? Any base from 2 through 36 would be allowed for the output base. Use single letters for numbers in the big bases like we did in hexadecimal.
