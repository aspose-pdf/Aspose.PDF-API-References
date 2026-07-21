---
title: "System::Xml::XmlNamespaceManager::GetNamespacesInScope método"
linktitle: "GetNamespacesInScope"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNamespaceManager::GetNamespacesInScope método. Devuelve una colección de nombres de espacios de nombres indexados por prefijo que pueden usarse para enumerar los espacios de nombres actualmente en alcance en C++."
type: docs
weight: 600
url: /es/cpp/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope method


Devuelve una colección de nombres de espacios de nombres indexados por prefijo que pueden usarse para enumerar los espacios de nombres actualmente en alcance.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alcance | XmlNamespaceScope | Un valor de enumeración que especifica el tipo de nodos de espacio de nombres que se devolverán. |

### ReturnValue

Una colección de pares de espacio de nombres y prefijo actualmente en alcance.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
