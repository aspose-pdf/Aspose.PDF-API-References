---
title: "System::Xml::XmlNodeReader::LookupNamespace метод"
linktitle: "LookupNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeReader::LookupNamespace метод. Разрешает префикс пространства имён в области текущего элемента в C++."
type: docs
weight: 2500
url: /ru/cpp/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace method


Разрешает префикс пространства имён в области действия текущего элемента.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | const String\& | Префикс, URI пространства имён которого вы хотите разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте пустую строку. Эта строка не обязана быть атомизирована. |

### ReturnValue

URI пространства имён, к которому привязан префикс, или **nullptr**, если соответствующий префикс не найден.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
