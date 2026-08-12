---
title: "Метод System::Xml::XmlAttribute::PrependChild"
linktitle: "PrependChild"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlAttribute::PrependChild. Добавляет указанный узел в начало списка дочерних узлов этого узла в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild method


Добавляет указанный узел в начало списка дочерних узлов этого узла.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | Элемент [XmlNode](../../xmlnode/) для добавления. Если это [XmlDocumentFragment](../../xmldocumentfragment/), всё содержимое фрагмента документа перемещается в список дочерних узлов этого узла. |

### ReturnValue

Добавленный [XmlNode](../../xmlnode/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
