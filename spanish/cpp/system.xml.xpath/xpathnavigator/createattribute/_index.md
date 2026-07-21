---
title: "Método System::Xml::XPath::XPathNavigator::CreateAttribute"
linktitle: "CreateAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XPath::XPathNavigator::CreateAttribute. Crea un nodo de atributo en el nodo de elemento actual utilizando el prefijo del espacio de nombres, el nombre local y el URI del espacio de nombres especificados con el valor indicado en C++."
type: docs
weight: 700
url: /es/cpp/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute method


Crea un nodo de atributo en el nodo de elemento actual usando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | String | El prefijo del espacio de nombres del nuevo nodo de atributo (si lo hay). |
| localName | String | El nombre local del nuevo nodo de atributo que no puede ser [String::Empty](../../../system/string/empty/) o **nullptr**. |
| namespaceURI | String | El URI del espacio de nombres para el nuevo nodo de atributo (si lo hay). |
| value | String | El valor del nuevo nodo de atributo. Si se pasa [String::Empty](../../../system/string/empty/) o **nullptr**, se crea un nodo de atributo vacío. |

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
