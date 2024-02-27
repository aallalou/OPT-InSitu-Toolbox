%--------------------------------------------------------------------------
% This file is part of the OPT InSitu Toolbox
%
% Copyright: 2024   XYZ
%
% License: GNU General Public License v3.0
% Contact: a.allalou@gmail.com
% Website: https://github.com/aallalou/OPT-InSitu-Toolbox
% If you use the this toolbox for your research, we would appreciate 
% if you would refer to the following paper:
%
% A. Allalou, Y. Wu, M. Ghannad-Rezaie, P. M. Eimon, and M. F. Yanik, “Automated
% deep-phenotyping of the vertebrate brain,” Elife, vol. 6, p. e23379, Apr. 2017.
%
%--------------------------------------------------------------------------

The major part of the code is written in MATLAB. The open source registration
toolbox elastix (http://elastix.isi.uu.nl/) is used for registration and 
must be installed before running the code. Other required toolboxes that 
need to be downloaded and installed are DIPimage (http://www.diplib.org/). For 
more information and full descriptoin of the OPT in situ workflow se the 
reference. 

 

 

System requirements
-------------------
Windows 7/8/10/11
Minimum RAM: 16GB RAM

License
-------
All code except the 3rd party code is coverd by the LICENSE.txt file. 
Files and folders covered by the LICENSE.txt file. 
example2_runRegistration.m
example1_ReconstructSingleFish.m
\registration
\tools



3rd Party
---------
All 3rd party code is placed in a separate folder and is not covered by the LICENSE.txt file.
All 3rd party code is covered by their respective license. 


*******readVTK and writeVTKRGB ************************************
Both functions are modified version of code written by Erik Vidholm
Center for Image Analysis, Uppsala University, Sweden
Erik Vidholm 2005
Erik Vidholm 2006
*******************************************************************

References:
------------

If you use any part of the OPT InSitu Toolbox code for your research, we 
would appreciate it if you would refer to the following paper:

"A. Allalou, Y. Wu, M. Ghannad-Rezaie, P. M. Eimon, and M. F. Yanik, 
“Automated deep-phenotyping of the vertebrate brain,” Elife, vol. 6, p. 
e23379, Apr. 2017."
