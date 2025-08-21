### Windows PowerShell Komut

1. **Get-Help**

   - Açıklama: PowerShell komutları hakkında yardım almanızı sağlar.
   - Örnek: `Get-Help Get-Process`

2. **Get-Command**

   - Açıklama: Kullanılabilir komutların listesini gösterir.
   - Örnek: `Get-Command`

3. **Get-Alias**

   - Açıklama: Komutların kısaltmalarını listeler.
   - Örnek: `Get-Alias`

4. **Set-Alias**

   - Açıklama: Kendi komut kısaltmalarınızı oluşturmanızı sağlar.
   - Örnek: `Set-Alias ll Get-ChildItem`

5. **Get-Process**

   - Açıklama: Çalışan işlemleri görüntüler.
   - Örnek: `Get-Process`

6. **Stop-Process**

   - Açıklama: Belirtilen bir işlemi sonlandırır.
   - Örnek: `Stop-Process -Name notepad`

7. **Start-Process**

   - Açıklama: Yeni bir işlem başlatır.
   - Örnek: `Start-Process notepad.exe`

8. **Get-Service**

   - Açıklama: Hizmetlerin durumunu listeler.
   - Örnek: `Get-Service`

9. **Stop-Service**

   - Açıklama: Bir hizmeti durdurur.
   - Örnek: `Stop-Service -Name Spooler`

10. **Start-Service**

    - Açıklama: Bir hizmeti başlatır.
    - Örnek: `Start-Service -Name Spooler`

11. **Restart-Service**

    - Açıklama: Bir hizmeti yeniden başlatır.
    - Örnek: `Restart-Service -Name Spooler`

12. **Get-EventLog**

    - Açıklama: Olay günlüklerini listeler.
    - Örnek: `Get-EventLog -LogName Application`

13. **New-Item**

    - Açıklama: Yeni bir dosya veya klasör oluşturur.
    - Örnek: `New-Item -Path C:\Example -ItemType Directory`

14. **Remove-Item**

    - Açıklama: Bir dosya veya klasörü siler.
    - Örnek: `Remove-Item -Path C:\Example`

15. **Copy-Item**

    - Açıklama: Bir dosya veya klasörü kopyalar.
    - Örnek: `Copy-Item -Path C:\Example -Destination D:\Backup`

16. **Move-Item**

    - Açıklama: Bir dosya veya klasörü taşır.
    - Örnek: `Move-Item -Path C:\Example -Destination D:\Backup`

17. **Get-Content**

    - Açıklama: Bir dosyanın içeriğini okur.
    - Örnek: `Get-Content -Path C:\Example\file.txt`

18. **Set-Content**

    - Açıklama: Bir dosyaya yeni içerik yazar.
    - Örnek: `Set-Content -Path C:\Example\file.txt -Value "Hello, World!"`

19. **Add-Content**

    - Açıklama: Bir dosyanın sonuna içerik ekler.
    - Örnek: `Add-Content -Path C:\Example\file.txt -Value "New Line"`

20. **Clear-Content**

    - Açıklama: Bir dosyanın içeriğini temizler.
    - Örnek: `Clear-Content -Path C:\Example\file.txt`

21. **Get-Location**

    - Açıklama: Geçerli çalışma dizinini görüntüler.
    - Örnek: `Get-Location`

22. **Set-Location**

    - Açıklama: Çalışma dizinini değiştirir.
    - Örnek: `Set-Location -Path C:\Example`

23. **Push-Location**

    - Açıklama: Geçerli dizini bir yığın üzerine kaydeder ve yeni bir dizine geçer.
    - Örnek: `Push-Location -Path D:\Backup`

24. **Pop-Location**

    - Açıklama: Push-Location ile kaydedilen dizine geri döner.
    - Örnek: `Pop-Location`

25. **Get-ChildItem**

    - Açıklama: Bir dizindeki dosya ve klasörleri listeler.
    - Örnek: `Get-ChildItem -Path C:\Example`

26. **Rename-Item**

    - Açıklama: Bir dosya veya klasörü yeniden adlandırır.
    - Örnek: `Rename-Item -Path C:\Example\file.txt -NewName renamed.txt`

27. **Test-Path**

    - Açıklama: Bir dosya veya klasörün var olup olmadığını kontrol eder.
    - Örnek: `Test-Path -Path C:\Example\file.txt`

28. **Get-Variable**

    - Açıklama: Tanımlı değişkenleri görüntüler.
    - Örnek: `Get-Variable`

29. **Set-Variable**

    - Açıklama: Yeni bir değişken tanımlar.
    - Örnek: `Set-Variable -Name example -Value "Hello"`

30. **Remove-Variable**

    - Açıklama: Bir değişkeni kaldırır.
    - Örnek: `Remove-Variable -Name example`

31. **Get-Item**

    - Açıklama: Belirtilen bir dosya veya klasör hakkında bilgi alır.
    - Örnek: `Get-Item -Path C:\Example\file.txt`

32. **Measure-Object**

    - Açıklama: Nesnelerle ilgili çeşitli ölçümler yapar.
    - Örnek: `Measure-Object -Path C:\Example\file.txt`

33. **Out-File**

    - Açıklama: Çıktıyı bir dosyaya yönlendirir.
    - Örnek: `Get-Process | Out-File -FilePath C:\Processes.txt`

34. **Export-Csv**

    - Açıklama: Veriyi CSV formatında dışa aktarır.
    - Örnek: `Get-Process | Export-Csv -Path C:\Processes.csv`

35. **Import-Csv**

    - Açıklama: Bir CSV dosyasını okur.
    - Örnek: `Import-Csv -Path C:\Processes.csv`
---

### 1. **Get-Help**
- Açıklama: Komutlar hakkında yardım alır.
- Örnek: `Get-Help Get-Process`

### 2. **Get-Command**
- Açıklama: Mevcut komutların listesini gösterir.
- Örnek: `Get-Command`

### 3. **Get-Process**
- Açıklama: Çalışan işlemleri listeler.
- Örnek: `Get-Process`

### 4. **Stop-Process**
- Açıklama: Bir işlemi durdurur.
- Örnek: `Stop-Process -Name notepad`

### 5. **Start-Process**
- Açıklama: Yeni bir işlem başlatır.
- Örnek: `Start-Process notepad.exe`

### 6. **Get-Service**
- Açıklama: Hizmetlerin durumunu görüntüler.
- Örnek: `Get-Service`

### 7. **Start-Service**
- Açıklama: Bir hizmeti başlatır.
- Örnek: `Start-Service -Name Spooler`

### 8. **Stop-Service**
- Açıklama: Bir hizmeti durdurur.
- Örnek: `Stop-Service -Name Spooler`

### 9. **Get-Location**
- Açıklama: Mevcut çalışma dizinini gösterir.
- Örnek: `Get-Location`

### 10. **Set-Location**
- Açıklama: Çalışma dizinini değiştirir.
- Örnek: `Set-Location -Path C:\Example`

### 11. **Get-ChildItem**
- Açıklama: Bir dizindeki dosya ve klasörleri listeler.
- Örnek: `Get-ChildItem`

### 12. **New-Item**
- Açıklama: Yeni bir dosya veya klasör oluşturur.
- Örnek: `New-Item -Path C:\Example -ItemType Directory`

### 13. **Remove-Item**
- Açıklama: Bir dosya veya klasörü siler.
- Örnek: `Remove-Item -Path C:\Example`

### 14. **Copy-Item**
- Açıklama: Dosyaları kopyalar.
- Örnek: `Copy-Item -Path C:\file.txt -Destination D:\Backup`

### 15. **Move-Item**
- Açıklama: Dosyaları taşır.
- Örnek: `Move-Item -Path C:\file.txt -Destination D:\Backup`

### 16. **Rename-Item**
- Açıklama: Bir dosyayı yeniden adlandırır.
- Örnek: `Rename-Item -Path C:\file.txt -NewName renamed.txt`

### 17. **Test-Path**
- Açıklama: Bir dosyanın varlığını kontrol eder.
- Örnek: `Test-Path -Path C:\file.txt`

### 18. **Get-Content**
- Açıklama: Bir dosyanın içeriğini okur.
- Örnek: `Get-Content -Path C:\file.txt`

### 19. **Set-Content**
- Açıklama: Dosyaya yeni içerik yazar.
- Örnek: `Set-Content -Path C:\file.txt -Value "Hello"`

### 20. **Add-Content**
- Açıklama: Dosyanın sonuna içerik ekler.
- Örnek: `Add-Content -Path C:\file.txt -Value "New Line"`

### 21. **Clear-Content**
- Açıklama: Bir dosyanın içeriğini temizler.
- Örnek: `Clear-Content -Path C:\file.txt`

### 22. **Out-File**
- Açıklama: Komut çıktısını bir dosyaya kaydeder.
- Örnek: `Get-Process | Out-File -FilePath C:\processes.txt`

### 23. **Get-Date**
- Açıklama: Geçerli tarihi ve saati gösterir.
- Örnek: `Get-Date`

### 24. **Write-Output**
- Açıklama: Konsola çıktı yazdırır.
- Örnek: `Write-Output "Merhaba Dünya"`

### 25. **Read-Host**
- Açıklama: Kullanıcıdan giriş alır.
- Örnek: `Read-Host "Adınızı girin"`

### 26. **Get-Alias**
- Açıklama: Komutların kısaltmalarını listeler.
- Örnek: `Get-Alias`

### 27. **Set-Alias**
- Açıklama: Kendi kısaltmanızı oluşturur.
- Örnek: `Set-Alias ll Get-ChildItem`

### 28. **Get-Variable**
- Açıklama: Tanımlı değişkenleri gösterir.
- Örnek: `Get-Variable`

### 29. **Set-Variable**
- Açıklama: Yeni bir değişken tanımlar.
- Örnek: `Set-Variable -Name myVar -Value 42`

### 30. **Remove-Variable**
- Açıklama: Bir değişkeni kaldırır.
- Örnek: `Remove-Variable -Name myVar`

### 31. **Measure-Object**
- Açıklama: Bir nesnenin özelliklerini ölçer.
- Örnek: `Get-ChildItem | Measure-Object`

### 32. **Where-Object**
- Açıklama: Belirli bir koşula uyan nesneleri filtreler.
- Örnek: `Get-Process | Where-Object {$_.CPU -gt 100}`

### 33. **Sort-Object**
- Açıklama: Nesneleri sıralar.
- Örnek: `Get-Process | Sort-Object -Property CPU`

### 34. **ForEach-Object**
- Açıklama: Her nesne için bir işlem gerçekleştirir.
- Örnek: `Get-Process | ForEach-Object {$_.Name}`

### 35. **Exit**
- Açıklama: PowerShell oturumunu kapatır.
- Örnek: `Exit`

### 36. **Get-ChildItem** 
- Açıklama: bir dosyanin konumunu bulur.
- Örnek: Get-ChildItem -Path C:\ -Recurse -Filter "dosyaadi.txt"


---

---
windowsun kendi listesinden çikardim 
 Name                                               Version    Source
-----------     ----                                               -------    ------
Alias           % -> ForEach-Object
Alias           ? -> Where-Object
Alias           ac -> Add-Content
Alias           asnp -> Add-PSSnapin
Alias           cat -> Get-Content
Alias           cd -> Set-Location
Alias           CFS -> ConvertFrom-String                          3.1.0.0    Microsoft.PowerShell.Utility
Alias           chdir -> Set-Location
Alias           clc -> Clear-Content
Alias           clear -> Clear-Host
Alias           clhy -> Clear-History
Alias           cli -> Clear-Item
Alias           clp -> Clear-ItemProperty
Alias           cls -> Clear-Host
Alias           clv -> Clear-Variable
Alias           cnsn -> Connect-PSSession
Alias           compare -> Compare-Object
Alias           copy -> Copy-Item
Alias           cp -> Copy-Item
Alias           cpi -> Copy-Item
Alias           cpp -> Copy-ItemProperty
Alias           curl -> Invoke-WebRequest
Alias           cvpa -> Convert-Path
Alias           dbp -> Disable-PSBreakpoint
Alias           del -> Remove-Item
Alias           diff -> Compare-Object
Alias           dir -> Get-ChildItem
Alias           dnsn -> Disconnect-PSSession
Alias           ebp -> Enable-PSBreakpoint
Alias           echo -> Write-Output
Alias           epal -> Export-Alias
Alias           epcsv -> Export-Csv
Alias           epsn -> Export-PSSession
Alias           erase -> Remove-Item
Alias           etsn -> Enter-PSSession
Alias           exsn -> Exit-PSSession
Alias           fc -> Format-Custom
Alias           fhx -> Format-Hex                                  3.1.0.0    Microsoft.PowerShell.Utility
Alias           fl -> Format-List
Alias           foreach -> ForEach-Object
Alias           ft -> Format-Table
Alias           fw -> Format-Wide
Alias           gal -> Get-Alias
Alias           gbp -> Get-PSBreakpoint
Alias           gc -> Get-Content
Alias           gcb -> Get-Clipboard                               3.1.0.0    Microsoft.PowerShell.Management
Alias           gci -> Get-ChildItem
Alias           gcm -> Get-Command
Alias           gcs -> Get-PSCallStack
Alias           gdr -> Get-PSDrive
Alias           get-process
Alias           ghy -> Get-History
Alias           gi -> Get-Item
Alias           gin -> Get-ComputerInfo                            3.1.0.0    Microsoft.PowerShell.Management
Alias           gjb -> Get-Job
Alias           gl -> Get-Location
Alias           gm -> Get-Member
Alias           gmo -> Get-Module
Alias           gp -> Get-ItemProperty
Alias           gps -> Get-Process
Alias           gpv -> Get-ItemPropertyValue
Alias           group -> Group-Object
Alias           gsn -> Get-PSSession
Alias           gsnp -> Get-PSSnapin
Alias           gsv -> Get-Service
Alias           gtz -> Get-TimeZone                                3.1.0.0    Microsoft.PowerShell.Management
Alias           gu -> Get-Unique
Alias           gv -> Get-Variable
Alias           gwmi -> Get-WmiObject
Alias           h -> Get-History
Alias           history -> Get-History
Alias           icm -> Invoke-Command
Alias           iex -> Invoke-Expression
Alias           ihy -> Invoke-History
Alias           ii -> Invoke-Item
Alias           ipal -> Import-Alias
Alias           ipcsv -> Import-Csv
Alias           ipmo -> Import-Module
Alias           ipsn -> Import-PSSession
Alias           irm -> Invoke-RestMethod
Alias           ise -> powershell_ise.exe
Alias           iwmi -> Invoke-WmiMethod
Alias           iwr -> Invoke-WebRequest
Alias           kill -> Stop-Process
Alias           lp -> Out-Printer
Alias           ls -> Get-ChildItem
Alias           man -> help
Alias           md -> mkdir
Alias           measure -> Measure-Object
Alias           mi -> Move-Item
Alias           mount -> New-PSDrive
Alias           move -> Move-Item
Alias           mp -> Move-ItemProperty
Alias           mv -> Move-Item
Alias           nal -> New-Alias
Alias           ndr -> New-PSDrive
Alias           ni -> New-Item
Alias           nmo -> New-Module
Alias           npssc -> New-PSSessionConfigurationFile
Alias           nsn -> New-PSSession
Alias           nv -> New-Variable
Alias           ogv -> Out-GridView
Alias           oh -> Out-Host
Alias           popd -> Pop-Location
Alias           ps -> Get-Process
Alias           pushd -> Push-Location
Alias           pwd -> Get-Location
Alias           r -> Invoke-History
Alias           rbp -> Remove-PSBreakpoint
Alias           rcjb -> Receive-Job
Alias           rcsn -> Receive-PSSession
Alias           rd -> Remove-Item
Alias           rdr -> Remove-PSDrive
Alias           ren -> Rename-Item
Alias           ri -> Remove-Item
Alias           rjb -> Remove-Job
Alias           rm -> Remove-Item
Alias           rmdir -> Remove-Item
Alias           rmo -> Remove-Module
Alias           rni -> Rename-Item
Alias           rnp -> Rename-ItemProperty
Alias           rp -> Remove-ItemProperty
Alias           rsn -> Remove-PSSession
Alias           rsnp -> Remove-PSSnapin
Alias           rujb -> Resume-Job
Alias           rv -> Remove-Variable
Alias           rvpa -> Resolve-Path
Alias           rwmi -> Remove-WmiObject
Alias           sajb -> Start-Job
Alias           sal -> Set-Alias
Alias           saps -> Start-Process
Alias           sasv -> Start-Service
Alias           sbp -> Set-PSBreakpoint
Alias           sc -> Set-Content
Alias           scb -> Set-Clipboard                               3.1.0.0    Microsoft.PowerShell.Management
Alias           select -> Select-Object
Alias           set -> Set-Variable
Alias           shcm -> Show-Command
Alias           si -> Set-Item
Alias           sl -> Set-Location
Alias           sleep -> Start-Sleep
Alias           sls -> Select-String
Alias           sort -> Sort-Object
Alias           sp -> Set-ItemProperty
Alias           spjb -> Stop-Job
Alias           spps -> Stop-Process
Alias           spsv -> Stop-Service
Alias           start -> Start-Process
Alias           stz -> Set-TimeZone                                3.1.0.0    Microsoft.PowerShell.Management
Alias           sujb -> Suspend-Job
Alias           sv -> Set-Variable
Alias           swmi -> Set-WmiInstance
Alias           tee -> Tee-Object
Alias           trcm -> Trace-Command
Alias           type -> Get-Content
Alias           wget -> Invoke-WebRequest
Alias           where -> Where-Object
Alias           wjb -> Wait-Job
Alias           write -> Write-Output

---