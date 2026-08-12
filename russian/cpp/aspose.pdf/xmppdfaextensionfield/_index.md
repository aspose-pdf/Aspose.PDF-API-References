---
title: "Aspose::Pdf::XmpPdfAExtensionField класс"
linktitle: "XmpPdfAExtensionField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XmpPdfAExtensionField класс. Эта схема описывает поле в структурированном типе. Она очень похожа на схему типа значения свойства PDF/A, но определяет поле в структуре вместо свойства. URI пространства имён схемы:  Требуемый префикс пространства имён схемы: pdfaField в C++."
type: docs
weight: 20300
url: /ru/cpp/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class


Эта схема описывает поле в структурированном типе. Она очень похожа на схему PDF/A Property Value Type, но определяет поле в структуре вместо свойства. URI пространства имён схемы: [http://www.aiim.org/pdfa/ns/field#](http://www.aiim.org/pdfa/ns/field#) Требуемый префикс пространства имён схемы: pdfaField.

```cpp
class XmpPdfAExtensionField : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Name](./get_name/)() const | Имя поля. Имена полей должны быть допустимыми именами XML‑элементов. |
| [get_ValueType](./get_valuetype/)() const | Тип значения поля, взятый из спецификации XMP 2004 года, или встроенной схемы расширения типа значения PDF/A. Предопределённые имена типов XMP или имена пользовательских типов. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Возвращает список XML‑элементов, представляющих поле в XML‑дереве. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&) | Инициализирует объект. |
## См. также

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
