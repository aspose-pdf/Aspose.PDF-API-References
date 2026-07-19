---
title: "System::Xml::XmlValidatingReader::LookupNamespace метод"
linktitle: "LookupNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlValidatingReader::LookupNamespace метод. Разрешает префикс пространства имён в области текущего элемента''s в C++."
type: docs
weight: 3400
url: /ru/cpp/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace method


Разрешает префикс пространства имён в области действия текущего элемента.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | const String\& | Префикс, чей Uniform Resource Identifier (URI) пространства имён вы хотите разрешить. Чтобы сопоставить пространство имён по умолчанию, передайте пустую строку. |

### ReturnValue

URI пространства имён, к которому привязан префикс, или **nullptr**, если соответствующий префикс не найден.

## См. также

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
