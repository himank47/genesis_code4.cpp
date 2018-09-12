code for posist

This is implemented in c++. This does not contain whole code and naming and syntax errors may be present as it was not executed in IDE. This just contains the logic for program as I understood. Eg. array length in C++ has been reduced to arr.len() instead of whole code for array length. Unknown values are considered to be input by owner.

Record contains entities mentioned with changes in datatype as per those available in c++. key is added in data(int) for encription. timestamp implemented with time.h library. unordered set used for hashing purposes

Functionalities implemented are:

    create genesis : Node created with memory allocation and various attributes are computed and added. ref node=NULL.

    create children: Nodes are added as children after checking their values are valid by comp to parent.

    verifiication: owner is verified by key he entered,. hash is recomputed and compared with prev values.

    edit value: value editted after checking with parent , childrens are removed.

    transferring ownership: old user enters his key his key is matched and then hash is recomputed and checked with stored values. if True thn new user enters his data.

    longest chain: found using recursive call to n children of node and adding 1 for each node found in path. Max values among all paths found are returned

    longest chain of genesis: run fn 6 with genesis node as param.
