# РЕЗУЛЬТАТЫ ВЫПОЛНЕНИЯ ДЗ
* Склонирован репозиторий с кодом для ДЗ
## Форматирование с помощью Prettier
1. Prettier установлен как default
2. Форматирование:
* До применения форматирования:  
const sayHelloLinting = (fName) => {console.log(`Look, how pretty it is, ${fName}`);};

sayHelloLinting('Oksana');
* После применения форматирования:  
const sayHelloLinting = (fName) => {
  console.log(`Look, how pretty it is, ${fName}`);
};

sayHelloLinting("Oksana");
* Отличие: содержимое первых фигурных скобок вынесено в отдельную строку

