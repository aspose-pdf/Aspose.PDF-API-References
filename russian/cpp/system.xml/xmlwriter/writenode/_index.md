---
title: "System::Xml::XmlWriter::WriteNode метод"
linktitle: "WriteNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlWriter::WriteNode метод. При переопределении в производном классе копирует всё из читателя в писатель и перемещает читатель к началу следующего sibling‑элемента в C++."
type: docs
weight: 2600
url: /ru/cpp/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) method


При переопределении в производном классе копирует всё из reader в writer и перемещает reader к началу следующего sibling.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | SharedPtr\<XmlReader\> | Класс [XmlReader](../../xmlreader/) для чтения. |
| defattr | bool | **true** — копировать атрибуты по умолчанию из [XmlReader](../../xmlreader/); иначе **false**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) method


Копирует всё из объекта XPathNavigator в writer. Позиция XPathNavigator остаётся неизменной.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| навигатор | SharedPtr\<XPath::XPathNavigator\> | XPathNavigator, из которого копировать. |
| defattr | bool | **true** для копирования атрибутов по умолчанию; иначе **false**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
