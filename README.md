# 756Project
PHMSCI756_Project

## This project structure is meant to be a streamlined example of data organization in protein structural determination
## Project structure will be as follows:
Mutational_Scan_Project
Subfolders:
  Output_Data
  Raw_Data
  Process_Scripts
Example data path
~/Mutational_Scan_Project/Output_Data/ddG_Scores/230116_singlemutantscan.txt
Main Folder: Mutational_Scan_Project

Subfolders:

Raw_Data: Contains unmanipulated data directly from mutational scans. Files within this directory/subdirectories are organized by PDB_ID. 

Output_Data: Contains mutational scan data that has been processed into summaries. Organized by mutation name (PDB). Bottom layer contains summaries of average ddG and reasoning behind the mutation along with suggested PyMOL structure files.

Process_Scripts: Contains Rosetta scripts and logs that perform and monitor mutational scan processes. 

Readme.txt: Discusses purpose and goal of this project in a plain text file.
