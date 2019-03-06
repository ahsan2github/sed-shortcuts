##### Replace (inplace) '../Data/Lookup' with '/experiment' in all files in directories matching the experssion whatever-the-name-* 
` find whatever-the-name-* -type f -exec sed -i 's+../Data/Lookup+/experiment+g' {} \;`

##### Find the pattern "TopSpeed": 1000, in file sample.json and replace with "TopSpeed": 200,
sed -i 's+"TopSpeed.*+"TopSpeed": 200,+' sample.json
##### Find files matching names findMe00, findMe001 etc. in the current directory
`find . -name "find*"`
