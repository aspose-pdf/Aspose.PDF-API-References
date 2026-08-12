---
title: "Método System::Xml::XPath::XPathNavigator::MoveToNext"
linktitle: "MoveToNext"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XPath::XPathNavigator::MoveToNext. Cuando se sobrescribe en una clase derivada, mueve el XPathNavigator al nodo hermano siguiente del nodo actual en C++."
type: docs
weight: 6000
url: /es/cpp/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() method


Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](../) al nodo hermano siguiente del nodo actual.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Ver también

* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToNext(String, String) method


Mueve el [XPathNavigator](../) al nodo hermano siguiente con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del siguiente nodo hermano al que se moverá. |
| namespaceURI | String | El URI del espacio de nombres del siguiente nodo hermano al que se moverá. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; **false** if there are no more siblings, or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToNext(XPathNodeType) method


Mueve el [XPathNavigator](../) al siguiente nodo hermano del nodo actual que coincide con el [XPathNodeType](../../xpathnodetype/) especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | XPathNodeType | El [XPathNodeType](../../xpathnodetype/) del nodo hermano al que se moverá. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise, **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Ver también

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
