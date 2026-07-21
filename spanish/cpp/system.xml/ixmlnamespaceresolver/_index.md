---
title: "Clase System::Xml::IXmlNamespaceResolver"
linktitle: "IXmlNamespaceResolver"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::IXmlNamespaceResolver. Proporciona acceso de solo lectura a un conjunto de asignaciones de prefijo y espacio de nombres en C++."
type: docs
weight: 400
url: /es/cpp/system.xml/ixmlnamespaceresolver/
---
## IXmlNamespaceResolver class


Proporciona acceso de solo lectura a un conjunto de asignaciones de prefijo y espacio de nombres.

```cpp
class IXmlNamespaceResolver : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) | Devuelve una colección de asignaciones de prefijo‑espacio de nombres definidas que están actualmente en alcance. |
| virtual [LookupNamespace](./lookupnamespace/)(const String\&) | Devuelve el URI del espacio de nombres asignado al prefijo especificado. |
| virtual [LookupPrefix](./lookupprefix/)(const String\&) | Devuelve el prefijo que está asignado al URI del espacio de nombres especificado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
