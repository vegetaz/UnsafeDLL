# UnsafeDLL
System.Runtime.CompilerServices.Unsafe.dll

```PowerShell
# URL của file DLL trên GitHub
$url = "https://github.com/vegetaz/UnsafeDLL/raw/master/4.0.30319/System.Runtime.CompilerServices.Unsafe.dll"

# Tải file DLL
$webClient = New-Object System.Net.WebClient
$dllBytes = $webClient.DownloadData($url)

# Load assembly từ byte array
[System.Reflection.Assembly]::Load($dllBytes)
```
