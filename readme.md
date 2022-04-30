Converter PDF usando:
https://cloudconvert.com/pdf-to-html

Incluir zoom (procurar por id="page-container"):
```<div id="page-container" style="zoom:33%">```

Incluir title:
```<title>Agenda Musical Ubá</title>```

Incluir favicon imediatamente após a tag <title>, ao final da tag <head>:
```<link rel="icon" type="image/x-icon" href="./music.ico">```

Fazer deploy:
```firebase deploy --only hosting```