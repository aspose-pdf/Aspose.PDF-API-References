---
title: "System::Xml::Resolvers::XmlPreloadedResolver::SupportsType método"
linktitle: "SupportsType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Resolvers::XmlPreloadedResolver::SupportsType método. Determina si el resolvedor admite otros Tipos además de solo Stream en C++."
type: docs
weight: 800
url: /es/cpp/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType method


Determina si el resolvedor admite otros tipos además de Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | El URI absoluto a comprobar. |
| tipo | const TypeInfo\& | El Tipo a devolver. |

### ReturnValue

**true** if the Type is supported; otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
