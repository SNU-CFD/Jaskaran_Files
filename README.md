# Jaskaran_Files
Files which have OpenFOAM tutorials for your help.

/*********************************************************************************************************************************/

O p e n F O A M     T u t o r i a l

The Temperature simulation of the T junction has been done here. 
I have created a T-junction using the pitzDaily case from the folder: tutorials/incompressible/simpleFoam/pitzDaily.
By adding new vertices, the mesh for the T-junction was created and the simulation was done using simpleFoam.
I have used the pitzDaily file from the folder: tutorials/basic/scalarTransportFoam/pitzDaily to simulate T.
The T and U files were changed by taking the U file from the latest case in the original simpleFoam pitzdaily case and replacing it in the pitzDaily_with_T folder and modifying the T file. 
scalarTransportFoam was run and the final temperature change/gradient was observed by allowing air to flow through only one inlet.
On running paraFoam in the pitzDaily_with_T folder, the simulation can be seen in paraView.

/*********************************************************************************************************************************/
