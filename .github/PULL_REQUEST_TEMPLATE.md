## Description
A few sentences describing the overall goals of the pull request's commits.

**Please check if the PR fulfills these requirements**
- [ ] The commit message follows our guidelines: https://github.com/adazzle/react-data-grid/blob/master/CONTRIBUTING.md
- [ ] Tests for the changes have been added (for bug fixes / features)
- [ ] Docs have been added / updated (for bug fixes / features)


**What kind of change does this PR introduce?** (check one with "x")
```
[ ] Bugfix
[x] Feature
[ ] Code style update (formatting, local variables)
[ ] Refactoring (no functional changes, no api changes)
[ ] Build related changes
[ ] CI related changes
[x] Other... Please describe: Update react and remove auto complete feature
```

**What is the current behavior?** (You can also link to an open issue here)
React Data Grid supports Auto Complete feature
And relies on `react and react-dom ~0.14.6`


**What is the new behavior?**
Should work normal without using autocomplete feature.
Will throw lots of `props` warning from React.



**Does this PR introduce a breaking change?** (check one with "x")
```
[ ] Yes
[x] No
```

If this PR contains a breaking change, please describe the impact and migration path for existing applications: ...


**Other information**:
Cannot use Autocomplete feature and throws `props` warnings by react.