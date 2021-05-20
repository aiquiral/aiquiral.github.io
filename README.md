# Sudoku Solver (Prolog)

Run by using the command

    problem(1,Rows), sudoku(Rows), maplist(portray_clause, Rows).


More problems- 

    puzzle(1, [[_,4,_,9,_,_,_,5,_],
               [2,_,_,_,_,_,_,4,_],
               [1,9,_,_,8,_,7,_,_],
               [5,_,_,_,_,_,1,_,_],
               [_,_,7,_,6,_,_,_,3],
               [_,_,_,_,3,_,8,9,_],
               [_,8,_,3,4,_,_,6,_], 
               [3,_,_,2,_,8,_,_,_],
               [_,_,_,_,_,_,_,_,_]]).

    puzzle(2, [[_,_,9,5,_,_,_,3,7],
               [1,3,7,9,_,_,_,5,2],
               [2,_,_,_,_,3,6,9,_],
               [3,5,2,_,1,_,_,_,6],
               [_,_,_,4,5,2,3,_,_],
               [_,8,1,_,3,_,2,_,_],
               [6,_,3,_,4,_,8,_,9],
               [5,2,_,_,_,1,_,6,_],
               [_,_,_,3,_,7,_,_,_]]).

    puzzle(3, [[_,5,_,1,_,_,_,_,_],
               [2,_,_,5,_,_,6,_,_],
               [1,_,_,_,8,_,2,_,_],
               [_,8,_,4,3,_,_,_,_],
               [_,_,_,_,_,_,_,4,_],
               [_,_,_,_,_,7,9,3,2],
               [_,4,_,6,7,_,_,_,_],
               [_,7,_,_,_,_,_,1,9],
               [9,_,_,_,_,8,_,_,_]]).
