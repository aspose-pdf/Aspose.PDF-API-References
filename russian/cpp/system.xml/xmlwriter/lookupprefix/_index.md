---
title: "System::Xml::XmlWriter::LookupPrefix метод"
linktitle: "LookupPrefix"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::LookupPrefix метод. При переопределении в производном классе возвращает ближайший префикс, определённый в текущей области пространства имён, для URI пространства имён в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix method


При переопределении в производном классе возвращает ближайший префикс, определённый в текущей области пространства имён для URI пространства имён.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | String | URI пространства имён, префикс которого вы хотите найти. |

### ReturnValue

Соответствующий префикс или **nullptr**, если в текущей области не найдено подходящего URI пространства имён.

## См. также

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
