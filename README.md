# AutoDataDeploy
Export data from MSSQL/Oracle to txt based files automatically

So why did we develop Auto Data Deploy (ADD)?

We wanted to make it very fast and easy to export sql queries from MSSQL/Oracle to existing text file templates.<br> 
These text file templates can be HTML, JS, JSON, XML, TXT etc. 

ADD allows you to update existing text templates in 2 different ways:<br>
- You can update a token named {{DATA}} with a data array. This is useful for population multi-line data arrays.<br>
- You can replace tokens in a file named {{TOKEN1}}, {{TOKEN2}} etc with data from a query. This is useful for updating headers, dates and other information.
