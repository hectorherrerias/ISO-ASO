## POWERSHELL

### Seleccionar el proceso que mas consuma

---

```powershell
Get-Process | Sort-Object cpu -Descending | select -First 1
```
! [] (C:\Users\hecto\Desktop\pruebagit\ISO-ASO\images\picture.jpg "Seleccionar el proceso que mas consuma")