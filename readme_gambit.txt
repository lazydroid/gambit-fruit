GambitFruit with a taste of Toga

(Just an experiment to make a blitz engine as GBF4bx is
good in blitz using Toga' search and GambitFruit' evaluation.
GBFruit likes to draw but is a hard engine to beat! This is
part of my oldies upgrades for single processors. This is one
of my favorite Ryan Benitez' engines.)

- added Razoring from Toga 1.4beta5c
- used Futility pruning from Toga 3.1.2 SE
- used History pruning from Toga 3.1.2 SE
- used material values from toga 3.1.2 SE
- egbb path at c:/egbb/


Denis P. Mendoza
computer.chess@hotmail.com


----------------------------------------
I think Pawn Shielding, King safety, and tropism can all be tuned for better results.
To turn off Lazy Eval set Chess knowledge to 500.
If you have any suggestions for piece square tables please email them to me.
I plan on giving many piece square tables to choose from for each piece in UCI options in future releases.  
For bitbases please go to the Scorpion download section at http://wbec-ridderkerk.nl/index.html
Put the bitbases in the egbb folder and make sure you have the egbbdll.dll in the folder with the bitbases.
For an opening book goto http://chessbazaar.mlweb.info/fruitbooks

Added:
Alternate piece square tables
Rook pawn score adjustment
Rook bishop bonus
Queen Knight bonus
Two Rook penalty
Two Knight penalty
Minor tuning to piece values
King tropism 
Side to move bonus
Rook on bad pawn file bonus
Pawns on Bishop colour penalty (fewer pawns is better for bishops and with one bishop you should not block it with your own pawns)
Improved pawn structure
New Lazy Eval
Rebel reductions with researches
Bitbases (using Scorpio bitbase files)
Contempt factor
More tuning options
Other small changes that likely affect nothing

Todo:
Pawn Ram handling
Tune extensions and reductions
better draw recog
Tune king safety with tropism
SMP
Clean up my bugs added to Fabians great code

Thank you to Fabian for Fruit 2.1, Thomas for Toga, and to Bryan Hofmann for the window compile.  
-----------------------------------------
