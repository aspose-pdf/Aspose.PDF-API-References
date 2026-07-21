---
title: "System::Xml::XPath::XPathNavigator::PrependChildElement método"
linktitle: "PrependChildElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::PrependChildElement método. Crea un nuevo elemento hijo al comienzo de la lista de nodos hijos del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor indicado en C++."
type: docs
weight: 6700
url: /es/cpp/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement method


Crea un nuevo elemento hijo al principio de la lista de nodos hijos del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados con el valor indicado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | String | El prefijo de espacio de nombres del nuevo elemento hijo (si lo hay). |
| localName | String | El nombre local del nuevo elemento hijo (si lo hay). |
| namespaceURI | String | El URI del espacio de nombres del nuevo elemento hijo (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| value | String | El valor del nuevo elemento hijo. Si se pasa [String::Empty](../../../system/string/empty/) o **nullptr**, se crea un elemento vacío. |

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
