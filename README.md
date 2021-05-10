# Programming-challenge-alephfellowship
This contains the programming challenge which was given for the Aleph Fellowship Programme


Programming Challenge
Players X and O
Cell => 
1	2	3
4	5	6
7	8	9

	Game begins with “X” at the centre => 5[Cell 5]
[_,_,_,_,X,_,_,_,_]
		
	X	
		

	When ‘O’ play at the centre left => 4 [ Cells 4]
[_,_,_,O,_,_,_,_,_]
		
O	X	
		

	When ‘X’ play at the top left => 1 [Cell 1]
[X,_,_,_,_,_,_,_,_,]
X		
O	X	
		

	When ‘O’ play at the bottom left => 7 [Cell 7]
[_,_,_,_,_,O,_,_,]
X		
O	X	
O		

	When ‘X’ play at the bottom centre => 8 [Cell 8]
[_,_,_,_,_,_,_,X,_]
X		
O	X	
O	X	

	When ‘O’ play at the top centre to block => 2 [Cell 2]
[_,O,_,_,_,_,_,_,]
X	O	
O	X	
O	X	
 
	When ‘X’ play at the top right side => 3 [cell 3]
[_,_,X,_,_,_,_,_,_]
X	O	X
O	X	
O	X	

	When ‘O’ play at the centre right side => 6 [cell 6]
[_,_,_,_,_,O,_,_,_]
X	O	X
O	X	O
O	X	

	When ‘X’ play at the bottom right => 9 [cell 9]
[_,_,_,_,_,_,_,_,X]
X
O	X
O	X	O
O	X	X

The output: Game end and x win, while O loses

Question 2
Take the operator  ⊕ (that is commutative and associative)
	a ⊕ b = (a + 1) (b+1) – 1 -> x ⊕ y = x+ y + xy
	a ⊕ b = (a + 1) (b+1) – 1 => x⊕y = (x+x)(y+1) – 1 = (n+1) – 1 = n
Therefore: [(1+1) (1+1/2) (1 + 1/3) …….. (1 + 1/2021) -1 ]
2[( 2+1)/2] [(3+31)/3] …….. ((2021+1)/2021) – 1]
= (2021 + 1 ) – 1
= 2021 – 1 = -2022 
