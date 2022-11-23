# AutoDataDeploy
Export data from MSSQL/Oracle to txt based files automatically

So why did we develop Auto Data Deploy (ADD)?

We wanted to make it very fast and easy to export sql queries from MSSQL/Oracle to existing text file templates.<br> 
These text file templates can be HTML, JS, JSON, XML, TXT etc.<br> 
We also wanted the ability to repeat this process automatically so we could refresh dashboards and other files via scheduled tasks.

ADD allows you to update existing text templates in 2 different ways:<br>
- You can update a token named {{DATA}} with a data array. This is useful for population multi-line data arrays.<br>
- You can replace tokens in a file named {{TOKEN1}}, {{TOKEN2}} etc with data from a query. This is useful for updating headers, dates and other information.

Learn more here: https://apbreports.com/auto-data-deploy.html

Auto Data Deploy is completely <a>free and open source</a> and we only ask for a Donation if your company benefits from using the software.<br>

[![](https://pics.paypal.com/00/s/N2MyZjYyY2YtYjhlNS00ODgyLTg5MDktNTk2OTUzZThlMWJk/file.PNG)](https://www.paypal.com/donate/?hosted_button_id=Q9J4PBF64EVEJ)

Typically in a static HTML web dashboard page you have a data array and several fields you want to update such as the date, title and others.
ADD could update an existing HTML template with this information instantly. The video below will show you exactly how this works.
The following web dashboard was created using ADD tool in just 2 seconds: <br>
https://apbreports.com/dashboards/demo/side-by-side-stack/demo.html

ADD handles data querying and exporting in a very efficient way and can export separate HTML pages in just milliseconds. This means you can refresh and upload an entire website very quickly. It is also quick and easy to automatically refresh your HTML pages, simply setup a windows schedule task to run the ADD processes. You may choose to refresh your HTML pages every 15 minutes, hourly, daily or monthly. You can also run multiple instances of the .NET application if you need to export large numbers of HTML files in parallel.
