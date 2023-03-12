# how it works

Let's say you got an excel report of a supermarket, in this report there are all the sales made in the last 3 months highly detailed and messed up. The report "supermarket_sales.xlxs" contains many informations and is a huge file and you want only know the total sales and divided by gender, for example how much males and famels have spended and about what, if electronics, toys, food, etc...

This python script takes only specific data from the main report and creates a new report with just the data you want to see and of which month.

(The executable file is 30MB size and is not present in this repository because GitHub allows only files of 25MB size.)
However it can be created just by using the terminal like so:
from the terminal go in the folder "Automated-Report" and type "pyinstaller --onefile 6.convert-to-exe.py.
Then a folder called "dist" will be created and inside will be the "6.convert-to-exe.exe" executable file and "pivot_table.xlsx" file.

Double click on the "6.convert-to-exe.exe" file and then insert just the month you want the report to be.

