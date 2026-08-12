---
title: "System::Xml::XmlReader::LookupNamespace метод"
linktitle: "LookupNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::LookupNamespace метод. При переопределении в производном классе разрешает префикс пространства имён в области текущего элемента в C++."
type: docs
weight: 3100
url: /ru/cpp/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace method


При переопределении в производном классе разрешает префикс пространства имён в области действия текущего элемента.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | const String\& | Префикс, URI пространства имён которого вы хотите разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте пустую строку. |

### ReturnValue

URI пространства имён, к которому привязан префикс, или **nullptr**, если соответствующий префикс не найден.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
