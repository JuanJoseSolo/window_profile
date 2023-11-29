# window_profile
- Enable run scripts -> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned [as admin on powershell session]
- Knowing the profile path -> $PROFILE.AllUsersAllHosts
- Creation of the user path -> if (!(Test-Path -Path $PROFILE)) {New-Item -ItemType File -Path $PROFILE -Force }
