---
title: "System::Xml::XmlReader::ReadSubtree метод"
linktitle: "ReadSubtree"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadSubtree метод. Возвращает новый экземпляр XmlReader, который можно использовать для чтения текущего узла и всех его потомков в C++."
type: docs
weight: 7000
url: /ru/cpp/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree method


Возвращает новый экземпляр [XmlReader](../), который можно использовать для чтения текущего узла и всех его потомков.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### ReturnValue

Новый экземпляр чтения XML, установленный в состояние [ReadState::Initial](../../readstate/). Вызов метода [XmlReader::Read](../read/) позиционирует новый читатель на узле, который был текущим до вызова метода [XmlReader::ReadSubtree](./).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
