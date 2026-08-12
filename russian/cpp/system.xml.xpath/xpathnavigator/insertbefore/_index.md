---
title: "Метод System::Xml::XPath::XPathNavigator::InsertBefore"
linktitle: "InsertBefore"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::InsertBefore. Возвращает объект XmlWriter, используемый для создания нового узла‑соседа перед текущим выбранным узлом в C++."
type: docs
weight: 4200
url: /ru/cpp/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() method


Возвращает объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания нового узла‑соседа перед текущим выбранным узлом.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### ReturnValue

Объект [XmlWriter](../../../system.xml/xmlwriter/) используется для создания нового соседнего узла перед текущим выбранным узлом.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) method


Создаёт новый соседний узел перед текущим выбранным узлом, используя XML‑содержимое указанного объекта [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | SharedPtr\<XmlReader\> | Объект [XmlReader](../../../system.xml/xmlreader/) позиционирован на XML‑данных нового соседнего узла. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) method


Создаёт новый соседний узел перед текущим выбранным узлом, используя указанные узлы в объекте [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | SharedPtr\<XPathNavigator\> | Объект [XPathNavigator](../) позиционирован на узле, который будет добавлен как новый соседний узел. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::InsertBefore(String) method


Создает новый соседний узел перед текущим выбранным узлом, используя указанную XML‑строку.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | String | Строка XML‑данных для нового соседнего узла. |

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
