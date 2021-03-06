# TOPCAT Analysis
`Author: Palvisha Sharma`

_This project was created as content for a course on Data Science at York University, Toronto, Canada._

------------------------------------

"Data cleaning and Analysis using Python and TOPCAT" focuses on data cleaning and the basic analysis of astronomical data accquired through TOPCAT.
The information provided below will discuss TOPCAT, the installation process, and how to search for data from various astronomical surveys on TOPCAT, as well as retrieving the data for analysis. 

------------------

# Table of Contents: 

 1. [What is TOPCAT?](https://github.com/palvisha13/TopCatAnalysis/blob/main/README.md#topcat-analysis)
 2. [TOPCAT installation for MacOS](https://github.com/palvisha13/TopCatAnalysis#for-macos) 
 3. [TOPCAT installation for Non- Mac: Unix based systems](https://github.com/palvisha13/TopCatAnalysis#unix-based-systems)
 4. [TOPCAT installation for Non-Unix based systems](https://github.com/palvisha13/TopCatAnalysis#non-unix-systems)
 5. [Retrieving the data set neded for this project](https://github.com/palvisha13/TopCatAnalysis#retrieving-data-from-topcat-to-analyze-in-python)

------------------

# What is TOPCAT?

TOPCAT stands for Tool for Operations on Catalogues  and Tables, and is an interactive software equipped with various facilities to visualize astronomical data. 
It is particularly useful in managing large sets of tabular data. 

A more detailed list of features and their functions can be found at this [link](http://www.star.bris.ac.uk/~mbt/topcat/#features).

----

# TOPCAT Installation
 
  
   ### For MacOS 
  > For Apple Mac users, the installation file can be downloaded at: <a href="http://www.star.bris.ac.uk/~mbt/topcat/topcat-full.dmg">MacOS X TOPCAT</a> 
  
   #### Troubleshooting for MacOS:
   When downloading and installing TOPCAT, you may run into an error that says: 
    
   _App can’t be opened because it is from an unidentified developer_
    
    1. In this case, move the `.dmg` installation file for TOPCAT from your `Downloads` 
    folder to `Applications` folder. 
   
    2. Open the installation file in the Applications folder by double clicking on the `.dmg` file. This will 
    unzip a READme and TOPCAT application file into the Applications folder. 
   
    3. In the "Applications" folder, find the TOPCAT application, right click on it and select "open". 
    This will override the error.
  
  
  ### For Non-MacOS 
  
  > Download one of two `.jar` files: 
  
  > [topcat_full_.jar]()
  
  > [topcat_lite.jar]()
  
   ##### **Unix based systems:** 
  
     run the command `chmod +x topcat` in the same directory the `.jar` file is downloaded to.
  
     run the command `topcat`
  
   ##### **Non-Unix systems:**
  
     run the command `chmod +x topcat`
  
     run the command `java -jar topcat-*.jar`.
   
 -------------------------------
 
 _This information was summarized from the [TOPCAT Documentation](http://www.star.bris.ac.uk/~mbt/topcat/). Visit this site for more information_
 
 
 ----
 
 # Retrieving data from TOPCAT to analyze in Python

##### 1. When you first open up TOPCAT, you will see a window that looks like this: 
![first window](topcat1.png)

##### 2. Select the "files" tab on the top left.

##### 3. We will be working with images from the Galex mission, so click on the image cone in the center: 

![vizieR](https://github.com/palvisha13/TopCatAnalysis/blob/main/Screen%20Shot%202021-01-11%20at%201.48.50%20AM.png)

##### 4. Select the registry "http://vao.stsci.edu/RegTAP/TapService.aspx"

##### 5. Enter the keyword "galaxies"

##### 6. Set the RA = 00 degrees and DEC = 20 degrees, with an angular size of 3 degrees.


![data retreival](https://github.com/palvisha13/TopCatAnalysis/blob/main/Screen%20Shot%202021-01-11%20at%202.04.38%20AM.png)

##### 7. Select the data set from the list that pops up:

![Group of Galaxies](https://github.com/palvisha13/TopCatAnalysis/blob/main/Screen%20Shot%202021-01-11%20at%202.05.20%20AM.png)

##### 8.  Select the "Save" icon on the top left. You will see a window like this:

![Galaxies](https://github.com/palvisha13/TopCatAnalysis/blob/main/Screen%20Shot%202021-01-11%20at%202.29.47%20AM.png)


##### 9. Change the Output Format to csv and choose where to save your csv file using the "System Brower". When you rename it, remember to add the extension ".csv". 

##### 12. Now you're ready to clean and analyze the data!
