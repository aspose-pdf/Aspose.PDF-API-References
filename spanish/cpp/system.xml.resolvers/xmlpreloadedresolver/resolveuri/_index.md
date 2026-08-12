---
title: "Método System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri"
linktitle: "ResolveUri"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri. Resuelve la URI absoluta a partir de las URIs base y relativa en C++."
type: docs
weight: 600
url: /es/cpp/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri method


Resuelve el URI absoluto a partir del URI base y relativo.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | El URI base usado para resolver el URI relativo. |
| relativeUri | String | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con el **baseUri** para crear un URI absoluto. |

### ReturnValue

La [Uri](../../../system/uri/) que representa la URI absoluta o **nullptr** si no se puede resolver la URI relativa.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
