---
title: "System::Xml::XmlResolver::SupportsType method"
linktitle: "SupportsType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlResolver::SupportsType method. Permite que el resolvedor devuelva tipos diferentes a Stream en C++."
type: docs
weight: 400
url: /es/cpp/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType method


Permite que el resolvedor devuelva tipos distintos a Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | El URI. |
| tipo | const TypeInfo\& | El tipo a devolver. |

### ReturnValue

**true** if the **type** is supported; otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
