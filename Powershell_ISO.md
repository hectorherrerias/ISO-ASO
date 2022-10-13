## POWERSHELL

### Seleccionar el proceso que mas consuma

---

```powershell
Get-Process | Sort-Object cpu -Descending | select -First 1
```

![Seleccionar el proceso que mas consuma](/images/Seleccionar_el_proceso_que_mas_consuma.png)

