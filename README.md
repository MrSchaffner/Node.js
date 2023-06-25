# Node.js
Projects created primarily using Node.js javscript runtime

## Projects

### [Live Market Indicator](https://github.com/MrSchaffner/Code-Summary/tree/master/Market_Indicator_CodeSummary)

An options market indicator created for financial club, The Goose Group. Connects Node.js server to Client JavaScript to display live Stock Market options data in an aesthetic format.


```bash
const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello Universe');
});
```