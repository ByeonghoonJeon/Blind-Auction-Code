Code for blind auction.
From every input line, it checks correctness of input type to prevent from errors. 

# 3 steps to use
1. Register your name.
2. Register your bid.
3. If there is other participants, type Y. To finish, type N.

As like real auction, if the biding price is duplicated, the first person becomes the winner.

# How it works?
This program requires real name. Thus only alphabet is available for the user input.
However, our real name includes period and blank as well in many cases. For this reason, "." and " " is temporarily removed to check the validity of input.

If name and biding price is collected, these information is piled to the dictionary. To avoid same name confusion, if a name is already in the dictionary, The program requires another name.

Consquently, this program filters the maximum value in the dictionary.
