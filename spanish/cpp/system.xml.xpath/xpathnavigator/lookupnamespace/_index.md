---
title: "System::Xml::XPath::XPathNavigator::LookupNamespace method"
linktitle: "LookupNamespace"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::LookupNamespace method. Devuelve el URI del espacio de nombres para el prefijo especificado en C++."
type: docs
weight: 4700
url: /es/cpp/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace method


Devuelve el URI del espacio de nombres para el prefijo especificado.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const String\& | El prefijo cuyo URI de espacio de nombres deseas resolver. Para coincidir con el espacio de nombres predeterminado, pasa [String::Empty](../../../system/string/empty/). |

### ReturnValue

Una [String](../../../system/string/) que contiene el URI del espacio de nombres asignado al prefijo de espacio de nombres especificado; **nullptr** si no se asigna ningún URI de espacio de nombres al prefijo especificado. La [String](../../../system/string/) devuelta está atomizada.

## Ver también

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
