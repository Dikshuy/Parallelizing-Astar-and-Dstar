> course project of ME766
# Parallelizing A-star algorithm
MODULE REQ:: \
  import pygame if it's not already there in your console(To import pygame for python3.... pip3 install pygame) \
 \
STEPS:: \
  1)map.txt contains the workspace in terms of 1s and 0s where 1 is a free cell and 0 is an occupied cell \
  2)run the below line in terminal \
    python3 graphics.py \
  3)give the dimensions of the MAP \
  4)Create map with the help of pygame creates(whites are free spaces, red/selected cells are blocks) \
  5)Press enter after creating the MAP \
  7)you can find a green colored solution path \
  8)use pause button to pause in the process of travelling and you can update map using pygame window and 
    then press enter to continue to travel towards destination \
 \
NOTE:: \
  a)In map the top-left cell has coordinates (0,0) \
    moving down increases x-value \
    moving right increases y-value. \
  b)astar.cpp is executed within the graphics.py itself \
    map.txt and solution.txt will be updated at 5th and 6th steps respectively \
 \
BUG:: \
  ROW AND COL ARE PREDIFINED TO VALUES 100,100 IN astar.cpp, HAVE TO CHANGE THEM TO VAR VALUES(line 5,6) \
 \
ADDITIONS REQ:: \
  1)feature mentioned in 47thline of graphics.py file(selecting multiple cells as a big obstacle) \
  2)saving map feature
