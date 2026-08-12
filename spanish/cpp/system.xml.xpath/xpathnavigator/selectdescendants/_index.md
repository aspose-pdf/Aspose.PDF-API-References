---
title: "Método System::Xml::XPath::XPathNavigator::SelectDescendants"
linktitle: "SelectDescendants"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XPath::XPathNavigator::SelectDescendants. Selecciona todos los nodos descendientes del nodo actual con el nombre local y el URI del espacio de nombres especificados en C++."
type: docs
weight: 7400
url: /es/cpp/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(String, String, bool) method


Selecciona todos los nodos descendientes del nodo actual con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre local de los nodos descendientes. |
| namespaceURI | String | El URI del espacio de nombres de los nodos descendientes. |
| matchSelf | bool | **true** para incluir el nodo de contexto en la selección; de lo contrario, **false**. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectDescendants(XPathNodeType, bool) method


Selecciona todos los nodos descendientes del nodo actual que tengan un [XPathNodeType](../../xpathnodetype/) coincidente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | XPathNodeType | El [XPathNodeType](../../xpathnodetype/) de los nodos descendientes. |
| matchSelf | bool | **true** para incluir el nodo de contexto en la selección; de lo contrario, **false**. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
