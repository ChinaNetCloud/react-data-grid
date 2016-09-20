**I'm submitting a ...**  (check one with "x")
```
[ ] bug report
[x] feature request
[ ] support request => Please do not submit support request here, instead see https://github.com/adazzle/react-data-grid/blob/master/CONTRIBUTING.md
```

**Current behavior**
React Data Grid supports Auto Complete feature
And relies on `react and react-dom ~0.14.6`

**Expected/desired behavior**
Removed Auto Complete feature
Updated `react and react-dom to 15.2.1`

**Reproduction of the problem**
None

**What is the expected behavior?**
Should work normal without using autocomplete feature.
Will throw lots of `props` warning from React.


**What is the motivation / use case for changing the behavior?**
We are using a theme that requires `react ^15.0.0` and other components, so
react data grid uses older version of react. ron-autocomplete package uses older
version of react.
So, we removed it and update the package with react.


