Level 0: **century1**

\> \$PSVersionTable.BuildVersion.ToString()

Level 1: **10.0.14393.5127**

\> (Get-Alias wget).Definition

OR

\> (Get-Alias wget).ResolvedCommandName

Level 2: **invoke-webrequest443**

\> (Get-ChildItem).Count

OR

\> (ls \| Measure-Object).Count

Level 3: **123**

\> (ls \'.\\Can you open me\\\').Name

Level 4: **49125**

\> \$env:USERDOMAIN

Level 5: **underthewire3347**

\> (Get-ChildItem -Directory).Count

Level 6: **197**

\> Get-ChildItem ..\\ -Recurse -File -Filter readme.\* \| gc

Level 7: **7points**

\> (Get-Content unique.txt \| Select-Object -Unique).Count

OR

\> (Get-Content .\\Unique.txt \| Sort-Object \| Get-Unique \|
Measure-Object).count

Level 8: **696**

\> ((gc .\\Word_File.txt).split(\" \"))\[160\]

Level 9: **pierid**

\> Get-WmiObject win32_Service -Filter \"DisplayName = \'Windows
Update\'\" \| Select-Object -Property Description \| ft -Wrap

Level 10: **windowsupdates110**

\> Get-ChildItem ..\\ \| Get-ChildItem -Recurse -File -Hidden
-ErrorAction SilentlyContinue \| Where-Object {\$\_.Name -ne
\'desktop.ini\'}

Level 11: **secret_sauce**

\> (Get-ADDomainController).Name

THEN

\> Get-ADComputer UTW -Properties Description

Level 12: **i_authenticate_things**

\> (gc .\\countmywords).split(\" \").count

OR

\> gc .\\countmywords \| Measure-Object -Word

Level 13: **755**

\> (Get-Content .\\countpolos \| ForEach-Object { \$\_ -split \'\\s+\' }
\| Where-Object { \$\_ -eq \'polo\' }).Count

OR

\> ((gc .\\countpolos).split(\" \") \| Where-Object { \$\_ -eq \'polo\'
}).Count

OR

\> ((Get-Content .\\countpolos) -split \'\\s+\' \| Where-Object { \$\_
-eq \'polo\' }).Count

Level 14: **153**

Level 15: FIN
