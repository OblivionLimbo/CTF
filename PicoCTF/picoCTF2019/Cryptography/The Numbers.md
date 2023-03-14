# The Numbers

We get an image, that shows a bunch of numbers, in what looks to be a flag format. 

![the_numbers](the_numbers.png)

But this in itself makes no sense, we need to turn it into letters. 

16 9 3 15 3 20 6 { 20 8 5 14 21 13 2 5 18 19 13 1 19 15 14 }

We know that the flag always starts with "picoCTF{", so we can figure out how this is encoded. 

p is the 16th letter of the alphabet, which matches our first number, so its mapped to the alphabet, where 1 = a and 2 = b, 3 = c and so on. 

We can now solve this, either manually or automatically.   
I used: https://www.dcode.fr/letter-number-cipher  
We then get the flag:   

picoCTF{THENUMBERSMASON}