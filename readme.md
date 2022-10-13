# Конвертер XML to JSON
## Сначала скачиваем файл xml2 из библиотеки [x2js](https://github.com/abdolence/x2js)
## Затем через синтаксис получаем необходимый результат
let x2js = new X2JS();
let xmlText = "<MyRoot><test>Success</test><test2><item>val1</item><item>val2</item></test2></MyRoot>";
let jsonObj = x2js.xml_str2json(xmlText);
console.log(jsonObj); 
