AprendendoJS.md
// testando alteração
<!DOCTYPE html>
<html>
<head>
<title>js04_ifelse.htm - if</title>
<meta http-equiv="Content-Type" content="text/html; cherset=utf-8"
<meta charset="utf-8"/>
</head>
<body>
<script language="JavaScript">
<!-->
/* Objetivo: Ler dois valores, independentemente da ordem em que foram digitados, e apresentá-los em ordem crescente. Com a utilização da decisão condicional composta (if...else), não há mais necessidade de definir uma terceira variável. */

/*Definição das variáveis*/
var js_n1;
var js_n2;

/*Entrada de dados*/
js_n1 = parseInt(window.prompt('Informe o valor do primeiro número:','00'));
js_n2 = parseInt(window.prompt('Informe o valor do segundo número:','00'));

/*Saída de dados sem classificação*/
document.write('Número 1 digitado = ' + js_n1);
document.write('<br> Número 2 digitado = ' + js_n2);

/*Saída de dados com classificação por decisão condicional composta (if...else) */
if (js_n1 < js_n2) {
	document.write('<p><b>Classificação em ordem crescente:</b>' + js_n1 + ' e ' + js_n2);
}
else {
	document.write('<p><b>Classificação em ordem crescente:</b>' + js_n2 + ' e ' + js_n1);
}

//-->
</script>
</body>
</html>