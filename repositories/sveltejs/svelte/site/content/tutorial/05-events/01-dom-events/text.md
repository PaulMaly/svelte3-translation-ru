---
title: События DOM
---

Ранее мы уже видели, что прослушивать любое событие в элементе можно при помощи директивы `on:`:
```html
<div on:mousemove={handleMousemove}>
	Позиция курсора мыши {m.x} x {m.y}
</div>
```