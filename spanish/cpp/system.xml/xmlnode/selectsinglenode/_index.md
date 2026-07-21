---
title: "System::Xml::XmlNode::SelectSingleNode método"
linktitle: "SelectSingleNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNode::SelectSingleNode método. Selecciona el primer XmlNode que coincide con la expresión XPath en C++."
type: docs
weight: 3900
url: /es/cpp/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) method


Selecciona el primer [XmlNode](../) que coincide con la expresión [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const String\& | La expresión [XPath](../../../system.xml.xpath/). |

### ReturnValue

El primer [XmlNode](../) que coincide con la consulta [XPath](../../../system.xml.xpath/) o **nullptr** si no se encuentra ningún nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Selecciona el primer [XmlNode](../) que coincide con la expresión [XPath](../../../system.xml.xpath/). Cualquier prefijo encontrado en la expresión [XPath](../../../system.xml.xpath/) se resuelve usando el [XmlNamespaceManager](../../xmlnamespacemanager/) proporcionado.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const String\& | La expresión [XPath](../../../system.xml.xpath/). |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) para usar al resolver espacios de nombres de prefijos en la expresión [XPath](../../../system.xml.xpath/). |

### ReturnValue

El primer [XmlNode](../) que coincide con la consulta [XPath](../../../system.xml.xpath/) o **nullptr** si no se encuentra ningún nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
