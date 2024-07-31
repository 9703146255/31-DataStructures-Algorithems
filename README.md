# 31-DataStructures-Algorithems
01]Bubble sort[if true swap, if false no swap]
it will compare adjacent if true swap, if false no swap
=========================================================
phase-1
-------
4 2 1 5 3
compare 4,2 if 4>2 true then ==> 2 4 1 5 3
compare 4,1 if 4>1 true then ==> 2 1 4 5 3
compare 4,5 if 4>5 false then ==> 2 1 4 5 3
compare 5,3 if 5>3 true then ==> 2 1 4 3 5       (5) one [bubble up]
--------------------------------------------------------------------

phase-2
-------
2 1 4 3 5
compare 2,1 if 2>1 true then ==> 1 2 4 3 5
compare 2,4 if 2>4 true then ==> 1 2 4 3 5
compare 4,3 if 4>5 false then ==> 1 2 3 4 5     
compare 4,3 if 4>5 false then ==> 1 2 3 4 5     (4,5) two  [bubble up]
-----------------------------------------------------------------------
phase-3
-------
compare 1,2 if 1>2 false then ==> 1 2 3 4 5
compare 2,3 if 2>3 false then ==> 1 2 3 4 5
compare 3,4 if 3>4 false then ==> 1 2 3 4 5
compare 4,5 if 4>5 false then ==> 1 2 3 4 5 (3 4 5) three bubbled up

phase-4
-------
compare 1,2 if 1>2 false then ==> 1 2 3 4 5
compare 2,3 if 2>3 false then ==> 1 2 3 4 5
compare 3,4 if 3>4 false then ==> 1 2 3 4 5
compare 4,5 if 4>5 false then ==> 1 2 3 4 5(2 3 4 5) four bubbled up
