---
title: "System::Xml::XmlResolver::ResolveUri method"
linktitle: "ResolveUri"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlResolver::ResolveUri method. Cuando se sobrescribe en una clase derivada, resuelve el URI absoluto a partir de los URIs base y relativo en C++."
type: docs
weight: 200
url: /es/cpp/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri method


Cuando se sobrescribe en una clase derivada, resuelve el URI absoluto a partir del URI base y los URIs relativos.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | El URI base usado para resolver el URI relativo. |
| relativeUri | String | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con el **baseUri** para crear un URI absoluto. |

### ReturnValue

El URI absoluto o **nullptr** si el URI relativo no puede resolverse.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
