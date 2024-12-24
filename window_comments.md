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



