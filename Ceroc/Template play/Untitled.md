```timer
ms: false
log: false


_timerUID:78a2277b-69a6-4335-9955-11911f1bcf7d
```

[[Routines|Beginners Routine:]] [Routine:: 6]
```dataviewjs
dv.paragraph("![[Routines#Routine " + dv.current().Routine + "]]")

```


---
### Move 1 (Beg Var)
[Move1:: [[Cradle Barrier Limbo]]]

```dataviewjs

let MoveFile = dv.page(dv.current().Move1)

dv.paragraph("[[" + MoveFile.file.name + "]]")

dv.el(
	'video',
	dv.el('source', "",
		{
			attr: { 
				src: MoveFile.video,
				type: "video/mp4"
				}
			}
		),
	{attr: {controls:""}}
)
dv.paragraph(`

--- start-column ---

Text displayed in column 1.

--- end-column ---

Text displayed in column 2.

--- end-multi-column

`);
//dv.paragraph("![[" + dv.current().Move1 + "#Video]]")
dv.paragraph("Beats: " + dv.page(dv.current().Move1).Beats)
```


Text displayed in column 1.

--- end-column ---

Text displayed in column 2.

--- end-multi-column
Start L
End R

---
### Move 2 ([[Classic Moves Index|Classic]])

[Move2:: Accordion Cleaver Anticlockwise]

```dataviewjs
dv.paragraph("[[" + dv.current().Move2 + "]]")

dv.paragraph("![[" + dv.current().Move2 + "#Video]]")
dv.paragraph("Beats: " + dv.page(dv.current().Move2).Beats)
```
On this move in this routine combine the return as the start of the cleaver
The return is part one, Cleaver on mens right hand side ladies left
Catch two hands on step back

---
### Move 3 (Int/Adv)
[Move3:: Wurlitzer]

```dataviewjs

dv.paragraph("[[" + dv.current().Move3 + "]]")

dv.paragraph("![[" + dv.current().Move3 + "#Video]]")
dv.paragraph("Beats: " + dv.page(dv.current().Move3).Beats)
```


---



