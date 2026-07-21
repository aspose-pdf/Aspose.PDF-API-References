---
title: "Método System::Xml::XPath::XPathNavigator::SelectChildren"
linktitle: "SelectChildren"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XPath::XPathNavigator::SelectChildren. Selecciona todos los nodos hijos del nodo actual que tienen el nombre local y el URI del espacio de nombres especificados en C++."
type: docs
weight: 7300
url: /es/cpp/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(String, String) method


Selecciona todos los nodos hijos del nodo actual que tengan el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre local de los nodos hijos. |
| namespaceURI | String | El URI del espacio de nombres de los nodos hijos. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectChildren(XPathNodeType) method


Selecciona todos los nodos hijos del nodo actual que coinciden con el [XPathNodeType](../../xpathnodetype/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | XPathNodeType | El [XPathNodeType](../../xpathnodetype/) de los nodos hijos. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
