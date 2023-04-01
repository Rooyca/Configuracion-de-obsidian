```dataview
Table ("![10](" + cover + ")") as Cover, titulo as Título, autor as Autor, categorias as Categorias, páginas as Páginas
From "Libros"
Where contains(estado, "reading")
```
