##### Replace (inplace) '../Data/Lookup' with '/experiment' in all files in directories matching the experssion whatever-the-name-* 
` find whatever-the-name-* -type f -exec sed -i 's+../Data/Lookup+/experiment+g' {} \;`

##### Find files matching names findMe00, findMe001 etc. in the current directory
`find . -name "find*"`
