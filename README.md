****************************************
          Short presentation
****************************************

The package SymmetricFunctions encodes the most standard symmetric functions basis (elementary, complete homegeneous, power sum, monomial and Schur) and their associated polynomials. The changes of basis between symmetric functions and the operation of plethysm is also implemented. Many associated combinatorial tools are present in this package (Young Tableaux, Littlewood Richardson coefficients, Kostka coefficients ...).
This package is necessary for the packages BrauerAlgebra and xBrauer to work properly. 

Author: Thomas Helpin. Affilated to the Institut Denis Poisson (France).


****************************************
          INSTALLATION NOTES 
****************************************


After extracting the archive, you'll find multiple files contained within a directory named SymmetricFunctions-$BranchName/. 
Rename this directory to SymmetricFunctions/ and place it in a location where Mathematica looks for external packages. 
To find these locations, check the values of $BaseDirectory and $UserBaseDirectory in your Mathematica installation. 
Specifically, you'll need to move the renamed directory into the Applications/ subdirectory of either of these paths.

For Wolfram Language versions before 14.1 use Mathematica instead of
Wolfram in the following links.

Linux:

   - system-wide installation (requires root priviledges):

        /usr/share/Wolfram/Applications/

   - single-user installation:

        $HOME/.Wolfram/Applications/

Mac OS:

   - system-wide installation (requires root priviledges):

        /Library/Wolfram/Applications/

   - single-user installation:

        /Users/<user>/Library/Wolfram/Applications/

MSWindows:

   - system-wide installation:

	C:\Program Files\Wolfram Research\Wolfram\<version>\AddOns\Applications\

   - single-user installation:

	C:\Users\<user>\AppData\Roaming\Wolfram\Applications\

   Beware that in Windows these directories might be hidden!


Documentation files and exemples (like Tutorial_SymmetricFunctions.nb, etc) are placed in the SymmetricFunctions/Documentation directory.

Then the packages can be loaded using unix style

        <<SymmetricFunctions/SymmetricFunctions.m

or Mathematica style

        <<SymmetricFunctions`

If you have any problem, don't hesitate to contact me at

thomas.helpin@gmail.com


