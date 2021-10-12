The download contains files corresponding to the results discussed in the paper titled "An Open-Source Python-Based Boundary-Element Method Code for the Three-Dimensional Zero-Froude, Infinite-Depth, Water-Wave Diffraction-Radiation Problem "

The following folders are present in this download:
1. OMHyD_VR0V1 Files : Contains the OMHyD code and examples.
2. Appendix A Files: Contains the Python codes discussed in Appendix A of the paper.
3. Non-dimensinalizaition excel sheet for ANSYS results.

*********************************************************************************************
RUNNING THE OMHyD examples
*********************************************************************************************
1. Download the OMHyD_VROV1 folder to a computer with Python 3.7 installed.
2. Open the Frond_End_Files folder.
3. Copy the required example front-end file and paste in the OMHyD_VROV1 folder.
4. Open the copied front-end file and run the code.
5. For examples with 'waves=off' in the front-end file, only the graphical result will be displayed on successful execution.
6. For examples with 'waves=on'in the front-end file, in addition to the graphical result displayed after successful execution, an 'am.txt' file, containing the hydrodynamic data, is generated and placed within the OMHyD_VROV1 folder.
7. To view the graphical output of the data present in the 'am.txt' file, double click the 'Plotter.py', specify the required plots by following the comments inside the 'Plotter.py' file, and run the program.
8. For some cases that require longer run times, the corresponding 'am.txt' and 'plt_file.csv' files are provided for ready refrence. To view the graphical ouput of the data contained in the 'am._<case_name>.txt' file, copy the file to the OMHyD_VROV1 folder containing the 'Plotter.py' file, or copy the 'Plotter.py' file into the folder containing the 'am._<case_name>.txt' file, rename the 'am._<case_name>.txt' to 'am.txt', and run the 'Plotter.py' code with required parameters. The data contained in the '.csv' files may be plotted with suitable plot generation software of choice.
*********************************************************************************************
RUNNING THE Appendix A examples
*********************************************************************************************
1. Download the Appendix A Files to a computer with PYTHON installed.
2. Open the required python code and run program.
*********************************************************************************************
ANSYS verification
*********************************************************************************************
1. ANSYS workbench file size exceeds the GitHub limit. Mail the author at savinvis@gmail.com to get the files.
2. The excel file contains formulae in the yellow coloured cells. Dimensional data from ANSYS is entered in the uncoloured cells the generate the corresponding non dimensionalized data.
****End****
