```dataview
table Difficulty, Beats, start-hand as "Start Hand", end-hand as "End Hand"
from #ceroc and #moves and #intermediates and "Ceroc/Intermediates"
where Type = "Classic"
sort Name asc
```
