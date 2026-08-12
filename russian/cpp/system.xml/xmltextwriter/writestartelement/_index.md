---
title: "Метод System::Xml::XmlTextWriter::WriteStartElement"
linktitle: "WriteStartElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlTextWriter::WriteStartElement. Записывает указанный начальный тег и связывает его с заданным пространством имён и префиксом в C++."
type: docs
weight: 3800
url: /ru/cpp/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement method


Записывает указанный открывающий тег и связывает его с заданным пространством имён и префиксом.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | const String\& | Префикс пространства имён элемента. |
| localName | const String\& | Локальное имя элемента. |
| ns | const String\& | URI пространства имён, которое следует связать с элементом. Если это пространство имён уже находится в области видимости и имеет связанный префикс, запись автоматически добавит и этот префикс. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
