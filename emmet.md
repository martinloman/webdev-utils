# Emmet abbreviations

Emmet är ett kraftfullt verktyg inbyggt i VS Code för att generera HTML och CSS.

## Exempel

Ett utropstecken.

```
!
```

Genererar en tom HTML-sida med doctype, head och body.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>

</body>
</html>
```

---

Generera en div med en klass.

```
div.wrapper
```

Genererar

```
<div class="wrapper"></div>
```

---

Lite mer avancerat

```
div.menu>ul>li*5>a.menu-item
```

Genererar en div med klass `menu` som innehåller en lista med 5 list items med en länk i varje som i sin tur har klassen `menu-item`.

```
<div class="menu">
  <ul>
    <li><a href="" class="menu-item"></a></li>
    <li><a href="" class="menu-item"></a></li>
    <li><a href="" class="menu-item"></a></li>
    <li><a href="" class="menu-item"></a></li>
    <li><a href="" class="menu-item"></a></li>
  </ul>
</div>
```
