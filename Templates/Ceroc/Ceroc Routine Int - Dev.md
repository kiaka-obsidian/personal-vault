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
[Move1:: [[]]]

```dataviewjs

let MoveFile = dv.page(dv.current().Move1)

//dv.paragraph("[[" + MoveFile.file.name + "]]")

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



```


```multi-column-start
ID: Move1
number of columns: 3
```

```dataviewjs
let MoveFile = dv.page(dv.current().Move1)
dv.paragraph("**Type:** " + MoveFile.Type)
dv.paragraph("**Demo:** " + MoveFile.Demo)
dv.paragraph("**Start Hand:** " + MoveFile['Start Hand'])

```

---end-column ---

```dataviewjs
let MoveFile = dv.page(dv.current().Move1)
dv.paragraph("**Difficulty:** " + MoveFile.Difficulty)
dv.paragraph("**Teach:** " + MoveFile.Teach)
dv.paragraph("**End Hand:** " + MoveFile['End Hand'])
```

--- end-column ---

```dataviewjs
let MoveFile = dv.page(dv.current().Move1)
dv.paragraph("**Beats:** " + MoveFile.Beats)
dv.paragraph("**Return:** " + MoveFile.Return)
```

--- end-multi-column 

> [!INFO]+ Move One Notes
> .

---


### Move 2 ([[Classic Moves Index|Classic]])

[Move2:: [[]]]


```dataviewjs

let MoveFile = dv.page(dv.current().Move2)

//dv.paragraph("[[" + MoveFile.file.name + "]]")

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

```


```multi-column-start
ID: Move2
number of columns: 3
```

```dataviewjs
let MoveFile = dv.page(dv.current().Move2)
dv.paragraph("**Type:** " + MoveFile.Type)
dv.paragraph("**Demo:** " + MoveFile.Demo)
dv.paragraph("**Start Hand:** " + MoveFile['Start Hand'])

```

---end-column ---

```dataviewjs
let MoveFile = dv.page(dv.current().Move2)
dv.paragraph("**Difficulty:** " + MoveFile.Difficulty)
dv.paragraph("**Teach:** " + MoveFile.Teach)
dv.paragraph("**End Hand:** " + MoveFile['End Hand'])
```

--- end-column ---

```dataviewjs
let MoveFile = dv.page(dv.current().Move2)
dv.paragraph("**Beats:** " + MoveFile.Beats)
dv.paragraph("**Return:** " + MoveFile.Return)
```

--- end-multi-column 

> [!INFO]+ Move Two Notes
> .

---
### Move 3 (Int/Adv)
[Move3:: [[]]]


```dataviewjs

let MoveFile = dv.page(dv.current().Move3)

//dv.paragraph("[[" + MoveFile.file.name + "]]")

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

```


```multi-column-start
ID: Move3
number of columns: 3
```

```dataviewjs
let MoveFile = dv.page(dv.current().Move3)
dv.paragraph("**Type:** " + MoveFile.Type)
dv.paragraph("**Demo:** " + MoveFile.Demo)
dv.paragraph("**Start Hand:** " + MoveFile['Start Hand'])

```

---end-column ---

```dataviewjs
let MoveFile = dv.page(dv.current().Move3)
dv.paragraph("**Difficulty:** " + MoveFile.Difficulty)
dv.paragraph("**Teach:** " + MoveFile.Teach)
dv.paragraph("**End Hand:** " + MoveFile['End Hand'])
```

--- end-column ---

```dataviewjs
let MoveFile = dv.page(dv.current().Move3)
dv.paragraph("**Beats:** " + MoveFile.Beats)
dv.paragraph("**Return:** " + MoveFile.Return)
```

--- end-multi-column 

> [!INFO]+ Move Three Notes
> 
---



