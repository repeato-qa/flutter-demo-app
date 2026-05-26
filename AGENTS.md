# Important Rules

- Use the `gh` CLI tool to inspect broken workflow runs
- Please write temp files into the project itself, since write operations outside of the repo can not be auto approved. Write them into a `temp/` directory and ignore that directory in git. You can use these temp files to store data between iterations.