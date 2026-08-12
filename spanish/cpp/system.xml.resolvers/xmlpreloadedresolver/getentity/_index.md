---
title: "Método System::Xml::Resolvers::XmlPreloadedResolver::GetEntity"
linktitle: "GetEntity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::Resolvers::XmlPreloadedResolver::GetEntity. Asigna un URI a un objeto que contiene el recurso real en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity method


Asocia un URI a un objeto que contiene el recurso real.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | El URI devuelto por la llamada a [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| rol | String | Actualmente no se usa. |
| ofObjectToReturn | const TypeInfo\& | El tipo de objeto a devolver. El [XmlPreloadedResolver](../) admite objetos Stream y objetos TextReader para URIs que se agregaron como [String](../../../system/string/). Si el tipo solicitado no es compatible con el resolvedor, se lanzará una excepción. Use el método XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) para determinar si un determinado **Type** es compatible con este resolvedor. |

### ReturnValue

Un objeto Stream o TextReader que corresponde a la fuente real.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
