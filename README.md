# Replace '../SolverData/Lookup' with '/experiment' in all files in in directories matching the experssion thermal-single-bead-scaling-ts* 
` find thermal-single-bead-scaling-ts* -type f -exec sed -i 's+../SolverData/Lookup+/experiment+g' {} \;`
