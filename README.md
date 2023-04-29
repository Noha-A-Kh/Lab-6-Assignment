# Lab-6-Assignment
## **Description:**    
- The program reads an ARXML file containing a list of containers, each with a unique ID, and reorders the containers alphabetically by their name sub- container “"SHORT-NAME"
- The program writes the reordered containers to a new ARXML file
- If the file is not having .arxml extension, the program triggeres a user defined checked exception “NotVaildAutosarFileException”.
- If the file is empty, the program triggeres a user defined unchecked exception “EmptyAutosarFileException” .
- The output file shall be named as the same of the input file concatenated with “_mod.arxml” e.g. if the input was named “Rte_Ecuc.arxml” then the output should be “Rte_Ecuc_mod.arxml”.
