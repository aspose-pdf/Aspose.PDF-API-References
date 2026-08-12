---
title: "System::Xml::XmlTextReader::GetNamespacesInScope método"
linktitle: "GetNamespacesInScope"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlTextReader::GetNamespacesInScope método. Devuelve una colección que contiene todos los espacios de nombres actualmente en alcance en C++."
type: docs
weight: 3400
url: /es/cpp/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope method


Devuelve una colección que contiene todos los espacios de nombres actualmente en alcance.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scope | XmlNamespaceScope | Un valor [XmlNamespaceScope](../../xmlnamespacescope/) que especifica el tipo de nodos de espacio de nombres a devolver. |

### ReturnValue

Un objeto IDictionary que contiene todos los espacios de nombres actualmente en alcance. Si el lector no está posicionado en un elemento, se devuelve un diccionario vacío (sin espacios de nombres).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
