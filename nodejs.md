## How to Install NodeJS
1. Open https://nodejs.org/
2. Click the Download button
3. Double-click the downloaded file to install Chrome

## Troubleshooting
On Windows, if you run `npm`, you might get an error like this:
```powershell
npm : File C:\Program Files\nodejs\npm.ps1 cannot be loaded because running scripts is disabled on this system.
For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ npm
+ ~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess
```
1. In your command line, run `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`
2. Run `npm` again
