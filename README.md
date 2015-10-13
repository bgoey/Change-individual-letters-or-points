# Change-individual-letters-or-points
This is a piece of code that lets you change a letter or a comma within a dataframe. 


replacecom=function(x){
  for(i in 1: length(colnames(x))){
    x[,i]=sub(",",".", x[,i])
  } 
  return(x)
}  
