# UnsafeDLL
System.Runtime.CompilerServices.Unsafe.dll

# URL của file DLL trên GitHub
```PowerShell
$url = "https://github.com/path/to/your/dll/System.Runtime.CompilerServices.Unsafe.dll"

# Tải file DLL
$webClient = New-Object System.Net.WebClient
$dllBytes = $webClient.DownloadData($url)

# Load assembly từ byte array
$assembly = [System.Reflection.Assembly]::Load($dllBytes)
```
