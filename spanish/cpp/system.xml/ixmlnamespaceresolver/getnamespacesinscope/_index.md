---
title: "System::Xml::IXmlNamespaceResolver::GetNamespacesInScope método"
linktitle: "GetNamespacesInScope"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::IXmlNamespaceResolver::GetNamespacesInScope método. Devuelve una colección de asignaciones de prefijo-espacio de nombres definidas que están actualmente en alcance en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope method


Devuelve una colección de asignaciones de prefijo‑espacio de nombres definidas que están actualmente en alcance.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scope | XmlNamespaceScope | Un valor [XmlNamespaceScope](../../xmlnamespacescope/) que especifica el tipo de nodos de espacio de nombres a devolver. |

### ReturnValue

Una colección IDictionary que contiene los espacios de nombres actualmente en alcance.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
