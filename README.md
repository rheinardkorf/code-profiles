# code-profiles

These are the VSCode code profiles that I use for Go, Node/JS, PHP and WordPress development.

Some are complete, others are not. 

To use clone this repo to your user folder and then run VSCode by setting the `--extensions-dir` and `--user-data-dir` attributes.

Example: 

```
code --extensions-dir ~/.code_profiles/wpdev/ext --user-data-dir ~/.code_profiles/wpdev/data
```

For extra good measure, setup some alias.

E.g.
``` bash
# vscode profiles
alias godev="code --extensions-dir ~/.code_profiles/godev/ext --user-data-dir ~/.code_profiles/godev/data"
alias wpdev="code --extensions-dir ~/.code_profiles/wpdev/ext --user-data-dir ~/.code_profiles/wpdev/data"
alias phpdev="code --extensions-dir ~/.code_profiles/phpdev/ext --user-data-dir ~/.code_profiles/phpdev/data"
alias jsdev="code --extensions-dir ~/.code_profiles/jsdev/ext --user-data-dir ~/.code_profiles/jsdev/data"
```
