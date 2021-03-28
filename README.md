# clear-temp-files-bat
clear temp files bat

## This is an <h2> 
  
`<del %Temp%\*.* /S /F /Q

del C:\Windows\Temp\*.* /S /F /Q

SET Path2Del=C:\Windows\Temp\

for /R "%Path2Del%" %%F in (.) DO IF NOT "%%F"=="%Path2Del%." (RD /S /Q "%%F") ELSE (Del /F /S /Q "%Path2Del%*")

SET Path2Del=%Temp%\

for /R "%Path2Del%" %%F in (.) DO IF NOT "%%F"=="%Path2Del%." (RD /S /Q "%%F") ELSE (Del /F /S /Q "%Path2Del%*")

echo Vse vremennyie faylyi i papki udaleny

pause

@echo ON
>`
