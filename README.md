# pdb_parser by: Andrea Rubbi
Python program that can identify the residues interacting between chains of a complex protein. 

This is a very basic program that needs as input a pdb file of inerest.
The goal of this program is to analyse the coordinates of residues in differnt 
chains to find out which of the actually interact.
Beeing part of a bigger project born to analyse the Hemoglobin complex,
it has an additional feature that allows to analyse also the interactions
with the Heme and Oxy groups.

Its usage is simple: run the program with the pdb file as input:
Ex $ ./pdb_parser pdb_file.pdb

Then it will ask you to select the firts chain and then its kind.
Just try it and you will see how easy is its functionality.

After that it will also ask for the second chain, the procedure it's the same as before.

It will then print a table whith all the interacting atoms of the interacting residues of 
both chains.

The printing format is quite nice as it's done using pandas.
The table is saved as Interactions_csv/Chain_Inter + chain1 + chain2 .csv

requirements:
 -- numpy --> python3 -m pip install numpy
 -- pandas --> python3 -m pip install pandas
 
 If you have any doubt or suggestion feel free to contact me.
 

