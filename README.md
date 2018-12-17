# extents 

There are two text files.

`extents.txt` contains a large number, 50M+, of lines like "X1 X2", where X1 and X2 are the start and the end of the corresponding extent (inclusively).

`points.txt` contains a large number, millions, of points, one point per line.

All numbers in the files are signed integers.

Write a program, for every line in points.txt, printing the number of extents the point belongs to, to the standard output.

Example:

extents.txt:
```
-1 20
3 5
8 9
```

points.txt:
```
25
4
7
9
```

Expected output:
```
0
2
1
2
```
