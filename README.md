# Blogger Template from Scratch

Código básico de criação de template para Blogger a partir do zero

Para utilizar, importe ou copie o conteúdo do arquivo em seu blog. 

Após importar, clique nos botões 'Formatar tema' e 'Reverter temas de widget para o padrão'.

```
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <title><data:view.title.escaped/></title>
    <b:include data='blog' name='all-head-content'/>
    <meta content='width=device-width, initial-scale=1.0' name='viewport'/>
    <b:skin><![CDATA[]]></b:skin>
  </head>
  <body>
<header>
<b:section class='header' id='header' maxwidgets='1' showaddelement='yes'>
  <b:widget id='Header1' locked='true' title='Teste (Cabeçalho)' type='Header'></b:widget>
</b:section>
</header>
<article>
<b:section class='main' id='main' preferred='yes' showaddelement='no'>
  <b:widget id='Blog1' locked='true' title='Postagens no blog' type='Blog'>
</b:widget>
</b:section>
</article>
<aside>
<b:section class='sidebar' id='sidebar' maxwidgets='' showaddelement='yes'>
  <b:widget id='HTML1' locked='false' title='Widget' type='HTML'>
</b:widget>
</b:section>
</aside>
<footer>
<b:section class='footer' id='footer' maxwidgets='' showaddelement='yes'>
  <b:widget id='HTML2' locked='false' title='Widget' type='HTML'>
    </b:widget>
</b:section>
</footer>
  </body>
</html>
```
