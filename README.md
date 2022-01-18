# MBLP213 Final Ödevi Dökümantasyonu
İşletim sistemi Final Ödevi
Ödev Konusu:
Powershell scripti ile powershell schedule job tasarlanacakır job ın çalıştırcağı komut içerik olarak; İşletim sisteminde arkada çalışan programları task manager mantığı ile izleyerek Cpu yüzdesi %10 veya yukarı işlemleribir log dosyası oluşturulup Örnek: "Task.log", içine zaman damgası ile "2021-01-10 13:12:04,634 text.exe Cpu 20%" uygulama isimleri ve cpu yüzdeleri kaydedilecektir
PowerShell Script Çalışma Mantığı
![image](https://user-images.githubusercontent.com/97967616/149961855-651333d0-3441-4dea-871c-cd17b0ba1671.png)

mantik

Kullanılan CMDLET
Get-WMIObject Win32_ComputerSystem
Get-Counter "\Process(*)% Processor Time"
$_.CookedValue / $CpuCores
