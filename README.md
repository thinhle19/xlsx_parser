# Financial Report Parser
A dummy project to extract data from financial reports companies, in demand MAX291's assignment; then aggregate them into 1 result file. I use core Java with a Java library call `Apache POI`, which bring us various methods to handle with spreadsheet file formats.
# How to use
`Step 1`: Clone this project to your machine.<br>
`Step 2`: Screenshot tables from the reports then extract its data to an `.xlsx` file (here I use [Nanonets](app.nanonets.com)).<br>
`Step 3`: Download extracted data, categorizing by compnany's stock symbol and time period (ex: `PLP_122012.xlsx`). <br>
`Step 4`: Create 2 folders `XXX/csv/` in folder `financial_data/` and put all your company's files in. Same with other companies. <br>
`Step 5`: Replace my `result.xlsx` file with yours. <br>
`Step 6`: Run `Main` and enter all your company stock symbol (**order must be same with your folder's one**). <br>
## P.S.
*This is just a basic project for me not to type data cell by cell got from Google (almost 1000 cells with 9-digit-numbers each, suck!) so I know the code is so dump, cause even me was hard to understand it after about 2 days. 😂*.



