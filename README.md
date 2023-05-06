# SciCommProjAsssig-MireiaCrespi
__Code publication for a collage assigment__

This code is an assigment from a subject done during the first course of Biomedical Ingeenering degree in Universitat Pompeu Fabra called "Principis de Diseny Biologic", where we started to programm using Python. The final assigment of this subject was making a Python code where we were able to play the famous game "4 in a line" with a friend or versus the computer.

This game starts asking the player if he/she wants to play with a friend (in the same computer) or versus the machine (the programm selects where the piece goes). Once this is selected, the game begins. The player(s) basically have to choose the row where they want to throw the piece using the Python Console. A "board" is displayed in each turn in order to see all the pieces and be able to choose better where to throw the next round, this board has this form:

                 | _ | _ | _ | _ | _ | _ | _ |             
                 | _ | _ | _ | _ | _ | _ | _ |           
                 | _ | _ | _ | _ | _ | _ | _ |  
                 | _ | _ | _ | _ | _ | _ | _ |  
                 | _ | _ | _ | _ | _ | _ | _ |
                 | _ | _ | _ | _ | _ | _ | _ | 
    
    
Where "|" separates the columns and "_ _"_ indicates where the pieces ara going to be. The pieces are represented with a "X" for player one and "0" for player two.

The game ends when one of players connect 4 pieces in a row, it can be horizontally, vertically or diagonally. The code checks after every throw if some of the players have won. When this happens, it is displayed on the Python Console who has been the winner. If the board is full and nobody has won, the code detects that there's a tie and it is shown in the Python Console.
