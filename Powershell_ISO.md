## POWERSHELL

### Seleccionar el proceso que mas consuma

---

```powershell
Get-Process | Sort-Object cpu -Descending | select -First 1
```

![Descripción de la imagen](picture.jpg)