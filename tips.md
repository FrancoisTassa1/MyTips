## My Tips


#### Powershell

Allow TLS 1.2 on old powershell version :

```
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
```
