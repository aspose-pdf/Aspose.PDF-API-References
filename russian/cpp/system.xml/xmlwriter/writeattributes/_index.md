---
title: "System::Xml::XmlWriter::WriteAttributes метод"
linktitle: "WriteAttributes"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::WriteAttributes метод. Когда переопределяется в производном классе, выводит все атрибуты, найденные в текущей позиции XmlReader, в C++."
type: docs
weight: 900
url: /ru/cpp/system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes method


Когда переопределяется в производном классе, выводит все атрибуты, найденные в текущей позиции в [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | SharedPtr\<XmlReader\> | [XmlReader](../../xmlreader/) из которого копировать атрибуты. |
| defattr | bool | **true** — копировать атрибуты по умолчанию из [XmlReader](../../xmlreader/); иначе **false**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
