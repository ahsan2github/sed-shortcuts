##### Replace (inplace) '../Data/Lookup' with '/experiment' in all files in directories matching the experssion whatever-the-name-* 
` find whatever-the-name-* -type f -exec sed -i 's+../Data/Lookup+/experiment+g' {} \;`
