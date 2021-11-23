# Covid-19_Data_Analysis_Using_Python_and_Tableau
This data science project is on Covid-19 data analysis using Python and Tableau. Here, the data is processed using Pandas and requests libraries of Python and analyzed it using tableau.

## Steps in this project:
- Data Collection: <br/> https://en.wikipedia.org/wiki/COVID-19_pandemic ~ This dataset is updated regularly hence, fits the choice. The relevant data is collected using web scrapping with **read_html** function of the Pandas library.

-	Data Cleaning: 
<br/> The data fetched contains the entire text of the web page along with all the HTML, CSS formatting and other meta data. Hence, we need to filter out the relevant data frame and clean the data which consists of:
    -	change column names
    -	delete rows in Pandas
    -	modify value using _RegEx_ in Pandas
    -	replace selected value in a column
    -	change datatype of a column
    
-	Data Organization: <br/> exported the processed data into an .xlx file that is to be alanalysed in Tableau.

-	Data Analysis with Tableau: <br/> an intereactive dashboard of worldwide map of countries and a timeline graph of total confirmed cases and total deaths worldwide.

### Which IDE was used for programming?
-> Spyder 5.0.3
