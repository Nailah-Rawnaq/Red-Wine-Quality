# Red-Wine-Quality
The link of the data set is [kaggle](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009). This dataset consist information about the wines and a marking on its quality from 0 to 10. So I try to seperate the the high quality wine *(wines that score 7 or more)* form low or moderate quality wine.  
For that purpose **I tried:**
  - Most important two variable *(determined by the linear regression model)* on two axis and then plot the points.
  - First two principal component on the two axis and then plot the points.
  - Linear Discrimints on the two axis and then plot the points.
  - UMAP on the two axis and then plot the points.

  
    
    
This repo constis of 
- The data set: 
  + Though the data file [winequality-red.csv](/winequality-red.csv) is in the kaggel but I keep a copy of this in my Github also
- The code file: 
  + The file [Data seperation.Rmd](/Data_seperation.Rmd) is a Rmarkdown file which contains all the codes for this analysis.
- The report file: 
  + The file [Data-seperation.pdf](/Data-seperation.pdf) is a pdf file which contains the report of this analysis.  
  *(When opening the pdf file in the github it will take some time or sometime lead to some error. One way is to relode the pdf file or can be downloded to the machine)*
