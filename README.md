# State Space Search Problem

Three jealous husbands and their wives need to cross a river using a single boat. At no time should any of the women be left in company 
with any of the men, unless her husband is present. The boat can carry up to two passengers and can not move by itself.

The problem is modeled as a state space search problem. The shores of the river are the edges where the couples are standing. Initially,
it is assumed that they are standing on the left edge in the sequence as wife1, wife2, wife3, husband1, husband2, husband3. We describe the 
position of each person through numbers, 0 for left shore and 1 for right, same conventions are used for the position of the boat.
At each current state, we search for the possible nextmoves and check if the conditions are fulfilled or not, we are also required to 
check the goal state condition.
