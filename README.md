# Contact Search Script
A simple POSIX-compliant shell script that uses ```awk``` to search through your contacts.

## How It Works
* The script asks the user to input a search term.
* It reads from ```~/contacts.txt```.
* Each contact entry is assumed to be separated by ``###```.
* It performs a case-insensitive match against the entire record.
* Matching records are printed to the terminal.

## Expected File Format

```
###  
Tim Taylor  
Address: Street 1, Berlin  
Phone: 01234 5678912  
###  
Sam Smith  
Phone: 09876 5432198 
###
```

