# Assignment_Three
You can see my code [here](https://dftorres1984.github.io/Assignment_Three/) 

#I had to redo my Freedom_House_2 (2003-2005) dataset because the years column were combined with the data. So I pivoted longer and then pivoted wider. I also checked the character of the columns, which I noticed the new Year column was a character string instead of numeric. I had to fix that, and I had to make sure the columns of Freedom_House_2 were exactly the same name was Freedom House database so I could combine them later 

#I checked the column Country across all datasets by using unique and setdiff. I converted the unique V-Dem and LIED country names to the ones in Freedom House dataset. 

#I then combined the Freedom House databses, arranged the database by Country and Year and then merged it with LIED and finally with V-DEM for the final database. 
