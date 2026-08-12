---
title: "System::Xml::XPath::XPathNavigator::GetAttribute método"
linktitle: "GetAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::GetAttribute método. Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados en C++."
type: docs
weight: 3800
url: /es/cpp/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute method


Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | El nombre local del atributo. **localName** distingue entre mayúsculas y minúsculas. |
| namespaceURI | String | El URI del espacio de nombres del atributo. |

### ReturnValue

Una [String](../../../system/string/) que contiene el valor del atributo especificado; [String::Empty](../../../system/string/empty/) si no se encuentra un atributo coincidente, o si el [XPathNavigator](../) no está posicionado en un nodo de elemento.

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
