---
title: "System::Xml::XmlUrlResolver::GetEntity método"
linktitle: "GetEntity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlUrlResolver::GetEntity método. Asocia un URI a un objeto que contiene el recurso real en C++."
type: docs
weight: 200
url: /es/cpp/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity method


Asocia un URI a un objeto que contiene el recurso real.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | El URI devuelto por la llamada a [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| rol | String | Actualmente no se usa. |
| ofObjectToReturn | const TypeInfo\& | El tipo de objeto a devolver. La implementación actual solo devuelve objetos Stream. |

### ReturnValue

Un objeto de tipo stream o **nullptr** si se especifica un tipo distinto de stream.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
