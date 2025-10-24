# BASICALLY THIS CAN BE INTERESTING hehe

Now, we have 3 people, 

Alice (who is sending the flag)
Bob (who is receiving the flag)
Eve (who ahem eavesdropped)

Now, the data that Alice is, ahem ahem, obfuscated, so we can't see anything. But shouldn't we worry, we have the bases of the qubits of data that she sent.

(e.g) 
?+ ?x ?+ ?+ ?x ?+ ?+ ?+ 

(TwT I know)
But let's not worry and go deep.

We also have Bob's bits as well
0+ 1+ 1x 0+ 1+ 0x 1+ 1+

WE ALSO HAVE EVE'S BITS AS WELL (yay)
1+ 0x 1+ 1+ 0x 1+ 1+ 1+

Let's see how we can solve this.

# HOW TO SOLVE THIS?

a) Alice_base == Bob_base

Alice -> + x x + x + + +
Bob   -> + + x + + x + +

Check for the same bits
Base pair 1 are same, so take Bob's first binary bit now (0).

But look at Base pair 2 are not same, so let's go for the next step.

b) If Alice_base != Bob_base,

Check if Alice_base == Eve_base
If yes, take Eve's binary bit

Let's check it for this base pair 2,
Alice -> x and Eve -> x
SAME
so take Eve's bit (0).

If you understood, do the same for the rest.

### Bit Pair 3 -> Take Eve's bit because there is mismatch (1)
### Bit pair 4 -> Take Bob's bit because it is same (0)
### Bit pair 5 -> Take Eve's bit because mismatch (0)
### Bit pair 6 -> Take Eve's bit because mismatch (0)
### Bit pair 7 -> Take Bob's bit because there is match (1)
### Bit pair 8 -> Take Bob's bit because there is match (1)

Now combine all the bits,

0 0 1 0 0 0 1 1

Now take the ASCII value of this binary

You will get 'C'

Hooray! We got the first letter

Now, see if you can decode this

### https://drive.google.com/drive/folders/1-29GY5-3AOpY9EajDpBND7s8c7qrlrPH?usp=sharing
### Who knows, there must be a flag waiting for you :)


