---
title: "System::Xml::XmlNode::SelectNodes método"
linktitle: "SelectNodes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNode::SelectNodes método. Selecciona una lista de nodos que coinciden con la expresión XPath en C++."
type: docs
weight: 3800
url: /es/cpp/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method


Selecciona una lista de nodos que coinciden con la expresión [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const String\& | La expresión [XPath](../../../system.xml.xpath/). |

### ReturnValue

Una [XmlNodeList](../../xmlnodelist/) que contiene una colección de nodos que coinciden con la consulta [XPath](../../../system.xml.xpath/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Selecciona una lista de nodos que coinciden con la expresión [XPath](../../../system.xml.xpath/). Cualquier prefijo encontrado en la expresión [XPath](../../../system.xml.xpath/) se resuelve usando el [XmlNamespaceManager](../../xmlnamespacemanager/) suministrado.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const String\& | La expresión [XPath](../../../system.xml.xpath/). |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) para usar al resolver espacios de nombres de prefijos en la expresión [XPath](../../../system.xml.xpath/). |

### ReturnValue

Una [XmlNodeList](../../xmlnodelist/) que contiene una colección de nodos que coinciden con la consulta [XPath](../../../system.xml.xpath/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
