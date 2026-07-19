---
title: "Метод System::Xml::XmlTextReader::LookupNamespace"
linktitle: "LookupNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlTextReader::LookupNamespace. Разрешает префикс пространства имён в области текущего элемента'' в C++."
type: docs
weight: 3700
url: /ru/cpp/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace method


Разрешает префикс пространства имён в области действия текущего элемента.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | const String\& | Префикс, URI пространства имён которого вы хотите разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте пустую строку. Эта строка не обязана быть атомизирована. |

### ReturnValue

URI пространства имён, к которому привязан префикс, или **nullptr**, если соответствующий префикс не найден.

## См. также

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
