
```timer
ms: false
log: false


_timerUID:78a2277b-69a6-4335-9955-11911f1bcf7d
```

[[Routines|Beginners Routine:]] [Routine:: ]
```dataviewjs
dv.paragraph("![[Routines#Routine " + dv.current().Routine + "]]")

```


---
### Move 1 (Beg Var)
[Move1:: [[DHR Shoulder Turnout]]]
```dataviewjs
const MoveFile = dv.current().Move1

dv.paragraph("![[" + MoveFile.file.Name + "#Video]]")
dv.paragraph("Beats: " + dv.page(dv.current().Move1).Beats)
```



---
### Move 2 ([[Classic Moves Index|Classic]])

[Move2:: DHR Shoulder Turnout]
```dataviewjs

dv.paragraph("![[" + dv.current().Move2 + "#Video]]")
dv.paragraph("Beats: " + dv.page(dv.current().Move2).Beats)
```

---
### Move 3 (Int/Adv)

---


