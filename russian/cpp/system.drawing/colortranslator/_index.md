---
title: "System::Drawing::ColorTranslator класс"
linktitle: "ColorTranslator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::ColorTranslator класс. Выполняет преобразования цветов. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.drawing/colortranslator/
---
## ColorTranslator class


Выполняет преобразования цветов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ColorTranslator
```

## Методы

| Метод | Описание |
| --- | --- |
| static [FromHtml](./fromhtml/)(const System::String\&) | Преобразует указанное представление цвета в формате HTML в эквивалентный объект [Color](../color/). |
| static [FromWin32](./fromwin32/)(int) | Преобразует указанный цвет [Windows](../../system.windows/) в эквивалентный объект [Color](../color/). |
| static [ToHtml](./tohtml/)(const Color\&) | Преобразует указанный объект [Color](../color/) в строковое представление эквивалентного цвета в формате HTML. |
## См. также

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
