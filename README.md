# B+ Tree
I have implemented B+ tree using C++.
 - [x] Search
 - [x] Insert
 - [x] Structuring the main Function
 - [x] Delete
# Usage
 1. Clone it to some place in your PC.
 2. Install Visual Studios Community Edition -2019.
 3. File->create new project with existing code.
 4. Take a chill beer Run the code and Enjoy. (PS. Create an issue if you find any bug. Will be happy to fix it :)) HAPPY CODING !!
# Example DataBase Schema :
 - see above picture pic.png
# What is the project actually?
It is kind of small version of database system. Where I have implemented the B+ Tree for fast and efficient access of files in the disc. Here database tuples will be stores as a .csv file in above folder corresponding FILE* will be saved in the leaf node. Above step is done to mimic the disc-block access.
# Pre-assumptions :
  1. We are making a right biased tree. By this we mean if maxLimits are even we will split them in such a way that right sibling has one element greater.

  2. Insertion is based on the primary key. Hence all the properties of the primary key has to be followed. No dublicate insertion has to be done with same primary key!
