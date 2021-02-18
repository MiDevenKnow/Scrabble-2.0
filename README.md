# Scrabble-2.0
The aim of the game are the same as those of https://github.com/MiDevenKnow/Scrabble

**Please read the original scrabble description**

# Easier Gameplay
In scrabble 2.0, to get a score for a word, the last letter played **should start a word** in any direction. This rule is
included to simplify the game. For example, if the following letters are on the board “tao” and
“b” is placed after “o”, 

if the space to the right down diagonal is empty, the string "boat" is formed.

If the space to the right up diagonal is empty, the string "b" is formed.

If the space to the left down diagonal is empty,the string "b" is formed.

**All Three strings are returned and checked to be valid.**
