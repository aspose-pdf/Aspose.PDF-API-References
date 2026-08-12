---
title: "System::Xml::XmlNamespaceManager::LookupNamespace método"
linktitle: "LookupNamespace"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNamespaceManager::LookupNamespace método. Devuelve el URI del espacio de nombres para el prefijo especificado en C++."
type: docs
weight: 800
url: /es/cpp/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace method


Devuelve el URI del espacio de nombres para el prefijo especificado.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const String\& | El prefijo cuyo URI de espacio de nombres deseas resolver. Para coincidir con el espacio de nombres predeterminado, pasa [String::Empty](../../../system/string/empty/). |

### ReturnValue

El URI del espacio de nombres para **prefix** o **nullptr** si no hay un espacio de nombres asignado. La cadena devuelta está atomizada. Para obtener más información sobre cadenas atomizadas, consulta la clase [XmlNameTable](../../xmlnametable/).

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
