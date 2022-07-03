#  <img src="https://user-images.githubusercontent.com/85083611/177042261-3f46e97d-0e43-4d31-94b8-2cb73a43363e.svg"  width="50" height="50" align="center" /> utilize-sass 
 
 Sass é a linguagem de extensão CSS de nível profissional mais madura, estável e poderosa  do mundo.

Sass usa o $ símbolo para tornar algo uma variável. Aqui está um exemplo:

> Variável Scss
```
$font-stack: Helvetica, sans-serif;
$primary-color: #333;

body {
  font: 100% $font-stack;
  color: $primary-color;
}
```
> Variável Sass
```
$font-stack: Helvetica, sans-serif
$primary-color: #333

body
  font: 100% $font-stack
  color: $primary-color
```

> Variável Css
```
body {
  font: 100% Helvetica, sans-serif;
  color: #333;
}
```

> Exemplo de alinhamento no Scss:
```
.container {
    height: 100vh;
    display: flex;
    .esquerdo {
        width: 50%;
        background-color: aquamarine;
    }
    .direito {
        width: 50%;
        background-color: blueviolet;
    }
}
```
![Captura de tela 2022-07-03 111005](https://user-images.githubusercontent.com/85083611/177043567-14dcbfad-6330-415a-ae57-03b9286806b3.png)
