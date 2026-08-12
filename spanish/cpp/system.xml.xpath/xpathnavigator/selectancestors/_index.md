---
title: "System::Xml::XPath::XPathNavigator::SelectAncestors método"
linktitle: "SelectAncestors"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::SelectAncestors método. Selecciona todos los nodos ancestros del nodo actual que tengan el nombre local y la URI de espacio de nombres especificados en C++."
type: docs
weight: 7200
url: /es/cpp/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(String, String, bool) method


Selecciona todos los nodos ancestros del nodo actual que tengan el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre local de los nodos ancestros. |
| namespaceURI | String | La URI del espacio de nombres de los nodos ancestros. |
| matchSelf | bool | Para incluir el nodo de contexto en la selección, **true**; de lo contrario, **false**. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados. Los nodos devueltos están en orden inverso al del documento.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectAncestors(XPathNodeType, bool) method


Selecciona todos los nodos ancestros del nodo actual que tengan un [XPathNodeType](../../xpathnodetype/) coincidente.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | XPathNodeType | El [XPathNodeType](../../xpathnodetype/) de los nodos ancestros. |
| matchSelf | bool | Para incluir el nodo de contexto en la selección, **true**; de lo contrario, **false**. |

### ReturnValue

Un [XPathNodeIterator](../../xpathnodeiterator/) que contiene los nodos seleccionados. Los nodos devueltos están en orden inverso al del documento.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
