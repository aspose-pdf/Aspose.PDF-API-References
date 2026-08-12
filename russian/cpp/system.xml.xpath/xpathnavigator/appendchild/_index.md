---
title: "System::Xml::XPath::XPathNavigator::AppendChild метод"
linktitle: "AppendChild"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::AppendChild метод. Возвращает объект XmlWriter, используемый для создания одного или нескольких новых дочерних узлов в конце списка дочерних узлов текущего узла в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() method


Возвращает объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания одного или нескольких новых дочерних узлов в конце списка дочерних узлов текущего узла.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### ReturnValue

Объект [XmlWriter](../../../system.xml/xmlwriter/) используется для создания новых дочерних узлов в конце списка дочерних узлов текущего узла.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) method


Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя XML‑содержимое указанного объекта [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | SharedPtr\<XmlReader\> | Объект [XmlReader](../../../system.xml/xmlreader/) позиционирован на XML‑данных нового дочернего узла. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) method


Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя указанные узлы в объекте [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | SharedPtr\<XPathNavigator\> | Объект [XPathNavigator](../) позиционирован на узле, который будет добавлен как новый дочерний узел. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::AppendChild(String) method


Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя указанную строку XML‑данных.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | String | Строка XML‑данных для нового дочернего узла. |

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
