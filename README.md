# Financial visualisation

The purpose of this project is to practise python by visualizing monthly spending in charts and show how much is user spending on different commodities.

Parts:
1. Load data from monthly spending pdf file
2. Parse data into json object with following properties:

`{
  date: date,
  amount: number,
  company: string,
  accountNumber: string
}`

3. Make two overview data structures:
- Daily sum of money change
- Monthly list of companies with sum of transactions over the whole month

4. Save the overviews into a json file.
5. Make a UI where user can see all transactions and charts by month.
6. Allow the user to add categories to companies
