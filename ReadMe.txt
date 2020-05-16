Thermo-mechanical-metallurgical Finite Elements (TmmFE) - Version 40.00.00
------------------------------------------------------------------------


NOTE: TmmFE No Longer Supported on Windows XP; 

All previous versions must be upgraded to Version 21.00.00 or later under Windows 2007

Some of the previous data files prepared under previous versions may not work correctly with Version 28.00.00 onwards


The Finite Element Solver for the Solution of 
Thermo-mechanical-metallurgical problems
---------------------------------------------

Hardware requirement
-------------------

TmmFE can be run on a PC with the following configuration:

Windows 2007 as OS
2GB RAM
1024 X 768 pixels or better display

A high end PC or a 64-bit workstation is suggested for
achieving the solution in reasonable time, particulalry for inverse heat 
conduciton problems. 

Dowloading LIMITED VERSION of TmmFE
-----------------------------------
The LIMITED VERSION of TmmFE  
with 60 days validity can be dowloaded from the official website of 'thermetsolutions.com'
or from the link and it comes free.

Installing TmmFE from the downloaded version or the CD you have received
------------------------------------------------------------------------

The folder that is downloaded / CD will come with a TmmFEsetup.exe file. 
Create a folder in a suitable drive for working with TmmFE
Right-click TmmFESetup.exe and 'Run as Administrator'
Choose your destination drive and folder from the combo box
The relevant folders and files for running TmmFE will be copied onto your PC/Laptop

Procuring License for Running TmmFE  
-----------------------------------

Follow the steps indicated below for getting a license to run TmmFE 
on your DESIGNATED COMPUTER(S).

1.   Click 'Start' at the left end of the lower panel on your desktop.
2.   Run 'cmd.exe' from the Run command in the panel that opens.
3.   Type 'IPConfig/All' and press 'Enter' in the window that appears.
      Your Windows IP Configuration will be displayed. 
4.   Copy the text display onto a text file (you may use either a .doc or a .txt file) 
      and email to TherMet Solutions as an attachment.
5.   You will receive a 'TmmFEGenLicense.dll' file by email.
6.   Copy and replace the TmmFEGenLicense.dll in the folder TmmFE where the software is installed

Running TmmFE
-----------------

Please make sure your PC on which TmmFE is installed is connected to the 
internet while starting a session.

Doubleclicking the TmmFE.exe file will open TmmFE with the Password form.

Type 'qwerty' - the default password (case sensitive) to begin a session with TmmFE.


Manuals
-------

The dowloaded folder / CD contains the .pdf documents of both the User Manual
and the Technical Manual of TmmFE. The documents 
can be opened with Adobe Acrobat V 5 or above. The Manuals are 
bookmarked on all the content heads. Be sure to expand the
Bookmark panel for zeroing on the topic of your interest.


Solved Problems
-------------------

The folder TmmFE Examples contain several solved problems which may be used for 
familiarizing with the software.


===============================================
 

Debugging and Enchancement Notes: 

40.00.00
Users of previous versions of TmmFE will heave to reinstall the software by executing TmmFESetup.exe which comes with version 40.00.00. Before you reinstall, please mmake sure that you backup previous data in the WorkingFolder. 

37.00.00
Analysis of quenching characteristics by ASTM Inconel Probe procedure upgraded with automated report
generation
 

35.00.00
(i) Ten-node variable metric tetrahedron implemented for 3D thermal analysis 
(ii) Idenification of thermocouple location for Inverse Heat Conduction problem automated. TmmFE now 
identifies the node nearest to the thermocouple location and moves the node to the correct location 
by moving the node automatically.

34.30.00
Access violation error in ALLResults file output fixed

34.00.00
Bugs in the Heat Treatment Module removed

32.00.00
The 'Edit Drawing' and 1-D Elements' features are removed from the pre-processor 

31.50.00
All the modules are available to the user for problem formulation without a valid license
User will have to obtain a valid license for running the simulatrion model
User can now run example problems in the folder TmmFE Examples
Streamline display for fluid flow problems based om streamfunction implemented

31.00.00
Solidification problems are now solved only by the non-linear enthalpy formulation 
Bugs in Postprocessor unit removed
Time steps for heating/ transferring and quenching now defined individually in heat treatment module
Convetive boundary form for heat treatment unit redefined
Eaxample problems fully tested
Maximum and minimum temperatures of steel components defined for water quenching
Steel Composition Data file format changed; those files formatted using Ver 19.00.00 onwards have to be reformatted

30.20.00
Facility for specifying boundary conditions for 2D heat treatment re-incorporated
Modeling latent heat during alloy steel quenching reformulated

29.70.00
TTT diagram from published data modified to include hypereutectoid steels
Additional outputs for computing latent heat incoroporated
Alternative formulae from literature for computing steel properties incorporated


29.50.00
Formula for carbon equivalent calculation now chosen by user  
Hardness model data modellin using JMatPro revised
Provision for redefining Bs temperture in TTT diagram introduced

29.00.00
Casting Heat Treatment module tested fully


28.00.00
IHCP extended to unknown HTC
New BC- Unknown HTC - implemented
Output file (.xls) naming convention changed to include Date and Time string
User controlled output correction (IHCP Module) for reducing temperature errors implemented
Simultaneous calculation of Sensitivity Coefficients implemented
User choice for overriding boundary error convergence (IHCP Module) for faster solutoin implemented
Importing GID files for 3D heat treatment implemented  

27.30.00
Error in temperature estimation (IHCP) automatically calculated and output (.xls files)
Material property model type and other details on solution convergence added to Simulation Notes
Serial solution for IHCP extended to Non-Linear Properties 

27.20.00
ASTM Quench Test Solver improved; cooling curve requires spline interpolation
Average cooling rate from 600 to 100 at 1 C interval defined as a new parameter
IHCP convergence error defined both as percentage and absolute values of temperature
Boundary segments and element sides/nodes specified on the boundaries included in Simulation Notes
'Sensors' page of the 'IHCP SOlver' form renamed as 'IHCP Parameters'
  
27.10.00
Nodal temperature history as Excel file output - bug removed 


27.00.00
'AllResults' file reformatted to remove 'End Of File' message; previous versions 
  not compatible with new file format
LIMITED VERSION with maximum of 100 nodes and 60 days validity released

26.00.00
Post processer for Reference Probe enhanced with CCT display
Choice of Solver type (Direct/Iterative) made available
IHCP extended to case hardening

25.00.00
Critical temperatures fine tuned.
TTT Data Base input form refined.
Serial solution for IHCP implemented for Linear Proeprties 
Future Time steps optimized at 2; Direct SOlver for Enthalpy based IHCP.  

24.00.00
Undoing Moving nodes under mesh edit was made possible
Austenite decmposition files in XLS were made available
Temperature as End condition was made available for IHCP
Material data base was corrected
End conditions for Alloy probe added

23.00.00
Running file name displayed in the Mainform
Excel Output file headers were made proper
Output files in excel format were made available for IHCP and other modules

22.00.00
Time Temp records for a selected node was properly written in the output folder
Hardness values in the AlloyQuench and CCT modules were made consistent
Output files in excel format introduced
Option for running simulation for 'specified time' replaced by 'End Temp' condition

21.00.00
JMatPro Hardnbess model replaced by TTT models
Cursor trace with Popup menu removed
Bianite end curve extended up to Ms 
Reading data for 'Previous' runs corrected

20.00.00  	
Statusbar made visible

