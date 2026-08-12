---
title: "System::Xml::XPath::XPathNavigator::LookupPrefix método"
linktitle: "LookupPrefix"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::LookupPrefix método. Devuelve el prefijo declarado para el URI de espacio de nombres especificado en C++."
type: docs
weight: 4800
url: /es/cpp/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix method


Devuelve el prefijo declarado para el URI del espacio de nombres especificado.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceURI | const String\& | El URI del espacio de nombres a resolver para el prefijo. |

### ReturnValue

Una [String](../../../system/string/) que contiene el prefijo de espacio de nombres asignado al URI de espacio de nombres especificado; de lo contrario, [String::Empty](../../../system/string/empty/) si no se asigna ningún prefijo al URI de espacio de nombres especificado. La [String](../../../system/string/) devuelta está atomizada.

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
