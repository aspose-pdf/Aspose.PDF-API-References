---
title: "System::Xml::XmlNode::SelectSingleNode метод"
linktitle: "SelectSingleNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNode::SelectSingleNode метод. Выбирает первый XmlNode, соответствующий выражению XPath в C++."
type: docs
weight: 3900
url: /ru/cpp/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) method


Выбирает первый [XmlNode](../), соответствующий выражению [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const String\& | Выражение [XPath](../../../system.xml.xpath/). |

### ReturnValue

Первый [XmlNode](../), соответствующий запросу [XPath](../../../system.xml.xpath/), или **nullptr**, если подходящий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Выбирает первый [XmlNode](../), соответствующий выражению [XPath](../../../system.xml.xpath/). Любые префиксы, найденные в выражении [XPath](../../../system.xml.xpath/), разрешаются с помощью предоставленного [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const String\& | Выражение [XPath](../../../system.xml.xpath/). |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/) для разрешения пространств имён префиксов в выражении [XPath](../../../system.xml.xpath/). |

### ReturnValue

Первый [XmlNode](../), соответствующий запросу [XPath](../../../system.xml.xpath/), или **nullptr**, если подходящий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
