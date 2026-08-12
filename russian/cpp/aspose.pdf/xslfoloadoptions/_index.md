---
title: "Aspose::Pdf::XslFoLoadOptions класс"
linktitle: "XslFoLoadOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XslFoLoadOptions класс. Представляет параметры для загрузки/импорта файла XSL-FO в pdf‑документ на C++."
type: docs
weight: 21200
url: /ru/cpp/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class


Представляет параметры загрузки/импорта файла XSL-FO в PDF‑документ.

```cpp
class XslFoLoadOptions : public Aspose::Pdf::XmlLoadOptions
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [ParsingErrorsHandlingTypes](./parsingerrorshandlingtypes/) | Исходный документ XSLFO может содержать ошибки форматирования. Этот enum перечисляет возможные стратегии обработки таких ошибок форматирования. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Базовый путь/URL, из которого ищутся относительные пути к внешним ресурсам (если есть), указанные в загруженном файле SVG. |
| [get_XsltArgumentList](./get_xsltargumentlist/)() const | XsltArgumentList для вставки значений в существующие параметры xls. |
| [set_BasePath](./set_basepath/)(const System::String\&) | Базовый путь/URL, из которого ищутся относительные пути к внешним ресурсам (если есть), указанные в загруженном файле SVG. |
| [set_XsltArgumentList](./set_xsltargumentlist/)(const System::SharedPtr\<System::Xml::Xsl::XsltArgumentList\>\&) | XsltArgumentList для вставки значений в существующие параметры xls. |
| [XslFoLoadOptions](./xslfoloadoptions/)() | Создаёт объект [XslFoLoadOptions](./) без данных xsl. |
| [XslFoLoadOptions](./xslfoloadoptions/)(const System::String\&) | Создаёт объект [XslFoLoadOptions](./) с данными xsl. |
| [XslFoLoadOptions](./xslfoloadoptions/)(const System::SharedPtr\<System::IO::Stream\>\&) | Создаёт объект [XslFoLoadOptions](./) с данными xsl. |
## См. также

* Class [XmlLoadOptions](../xmlloadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
