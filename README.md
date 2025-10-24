# PowerBI_Projects
Data Cleaning Procedure

Dataset titled "hr_dataset" has been imported into Power BI.																		
Converted the first row into headers.																		
																		
Age																		
Changed the format of the Age column to whole numbers.																		
(Right-clicked the header - change type - Whole number)																		
Further converted the Age column into the absolute values to eliminate the negative values.																		
(Right-clicked the header - Transform - Absolute value																		
																		
Salary																		
Changed the format of the column to whole numbers.																		
Converted entries in the cell into Absloute values																		
																		
EmployeeID																		
Converted all letters in the entries into uppercase. (Right-clicked the header - Transform - UPPERCASE)																		
																		
Repeated the above step for Gender, Department and JobTitle.																		
																		
HireDate																		
Chaged the column format to Date. (Right-clicked the header - change type - Date)																		
																		
Removed all Errors from the entire dataset.																		
Removed all Duplicates from the dataset.																		
Removed all unwanted spacing from each column using trim function. (Right-clicked the header - Transform - Trim)																		
The above step applies to only columns in the TEXT format i.e. EmployeeID, Gender, Department, and JobTitle.																		
																		
Handling all "nan" values.																		
I replaced all "nan" values with empty spaces. (Select header - Replace Values - Enter the value you want to find(NAN) and what you want to replace it with (leave it blank) in the given boxes - OK)																		

CHALLENGES FACED
Missing values within the dataset.
