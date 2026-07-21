---
title: "System::Xml::XPath::XPathNavigator::MoveToChild método"
linktitle: "MoveToChild"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::MoveToChild método. Mueve el XPathNavigator al nodo hijo con el nombre local y el URI de espacio de nombres especificados en C++."
type: docs
weight: 5200
url: /es/cpp/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) method


Mueve el [XPathNavigator](../) al nodo hijo con el nombre local y el URI de espacio de nombres especificados.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del nodo hijo al que moverse. |
| namespaceURI | String | El URI del espacio de nombres del nodo hijo al que moverse. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToChild(XPathNodeType) method


Mueve el [XPathNavigator](../) al nodo hijo del [XPathNodeType](../../xpathnodetype/) especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | XPathNodeType | El [XPathNodeType](../../xpathnodetype/) del nodo hijo al que moverse. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Ver también

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
