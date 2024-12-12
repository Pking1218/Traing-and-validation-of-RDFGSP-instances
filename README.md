nCells = ...;  # the number of cells
nMachines = ...; # the machines within the cell
nGroups=...; #the number of families
nJobs=...; #the number of jobs within the families
ProcessingTime=...;# Multidimensional array: the processing time of jobs within the familie on the machine for each flow, size = (2, nMachines, nGroups, the maximum value of jobs within each family)
TransferTime=...; #Multidimensional array: the transfer time between the cells, size = (nCells, nCells)
SetupTime=...; #Multidimensional array: the setup time of families on the machines, size=(2, nMachines, nGroups) 
xx=...; #Multidimensional array: the number of ones in a certain column represents the number of jobs in the corresponding family, size=(nJobs, nGroups). 
