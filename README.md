# PowerShell
### Intro
- formally codenamed monad
- built on .NET Core
- focused around objects enabling rich sequences to be created which can perform complex tasks
- uses verb-noun pair command naming for cmdlets
- Powershell ISE features intellisense, scripting and debugging and help windows

- Aliases allow you to write commands in shortform
```bash
# To list all the aliases
get-alias
```
- to print output to the shell, its:
```bash
write-output "hello world"
```
- if you want to run multiple commands on one line, you can do that by using semi colons ` write-output "hello world"; get-service a*;`
