# awk

Awk is a scripting language used for manipulating data.  

It searches one or more files to see if they contain lines that matches with the specified patterns and then perform the associated actions. 

## What is it used for? 

AWK Operations: 
- Scans a file line by line 
- Splits each input line into fields 
- Compares input line/fields to pattern 
- Performs action(s) on matched lines 


Syntax:

``` cmd
awk options 'selection _criteria {action }' input-file > output-file

```

``` cmd
awk -f program-file
```

Reads the AWK program source from the file program-file, instead of from the first command line argument.

```cmd
awk -F fs
```

Use fs for the input field separator

```cmd
awk 'length($0) == "length"' "filename.txt"
```
Finds and prints lines with exactly an amount of characters in a specific file

