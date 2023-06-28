Converter PDF usando:
https://cloudconvert.com/pdf-to-html

Colar HTML gerado no index.html

Incluir zoom (procurar por id="page-container"):
```<div id="page-container" style="zoom:77%">```

Incluir title:
```<title>Agenda Musical Ubá</title>```

Incluir favicon imediatamente após a tag <title>, ao final da tag <head>:
```<link rel="icon" type="image/x-icon" href="./music.ico">```

Fazer deploy:
```firebase logout```
```firebase login```
```firebase deploy --only hosting```