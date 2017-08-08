# JS-CHALLENGE

Reddit Daily Programming Challenge #325 - Color Maze

First rough pass at a maze traversal for a color maze given a sequence of colors. Brand new to Javascript, therefor the code is not optimized and somewhat hacky.



## Solution
Input is given as a text file, taken in as an array. The first line is the sequence to use for solving the maze. 
```
Input (mazeData_2.txt):
R O Y P O
R R B R R R B P Y G P B B B G P B P P R
B G Y P R P Y Y O R Y P P Y Y R R R P P
B P G R O P Y G R Y Y G P O R Y P B O O
R B B O R P Y O O Y R P B R G R B G P G
R P Y G G G P Y P Y O G B O R Y P B Y O
O R B G B Y B P G R P Y R O G Y G Y R P
B G O O O G B B R O Y Y Y Y P B Y Y G G
P P G B O P Y G B R O G B G R O Y R B R
Y Y P P R B Y B P O O G P Y R P P Y R Y
P O O B B B G O Y G O P B G Y R R Y R B
P P Y R B O O R O R Y B G B G O O P B Y
B B R G Y G P Y G P R R P Y G O O Y R R
O G R Y B P Y O P B R Y B G P G O O B P
R Y G P G G O R Y O O G R G P P Y P B G
P Y P R O O R O Y R P O R Y P Y B B Y R
O Y P G R P R G P O B B R B O B Y Y B P
B Y Y P O Y O Y O R B R G G Y G R G Y G
Y B Y Y G B R R O B O P P O B O R R R P
P O O O P Y G G Y P O G P O B G P R P B
R B B R R R R B B B Y O B G P G G O O Y
```

Output:
```
Maze Path
_,_,_,_,_,_,_,_,_,_,_,_,_,_,_,_,_,_,_,_,
 , , , , , , ,P,Y, , , , , , , , , , , ,
 , , , , , , , ,R, , , , , , , , , , , ,
 , , , , , , , ,O, , , , , , , , , , , ,
 , , , , , , , ,O, ,R, , , , , , , , , ,
 , , , , , , , ,P,Y,O, , , , , , , , , ,
 , , , , , , , , , ,P, , , , , , , , , ,
 , , , , , , , , ,O,Y, , , , , , , , , ,
 , , , , , , , , ,R, , , , , , , , , , ,
 , , , , , , , ,P,O, , , , , , , , , , ,
 , , , , , , ,O,Y, , , , , , , , , , , ,
 , , , , , ,O,R, , , , , , , , , , , , ,
 , , , , , ,P, , , , , , , , , , , , , ,
 , , , , , ,Y, , , , , , , , , , , , , ,
 , , , , , ,O, , , , , , , , , , , , , ,
 , , , , ,O,R, , , , , , , , , , , , , ,
 , , , ,R,P, , , , , , , , , , , , , , ,
 , , ,P,O,Y, , , , , , , , , , , , , , ,
 , , ,Y, , , , , , , , , , , , , , , , ,
 , , ,O, , , , , , , , , , , , , , , , ,
 ```
