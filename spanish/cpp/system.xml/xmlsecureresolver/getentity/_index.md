---
title: "System::Xml::XmlSecureResolver::GetEntity method"
linktitle: "GetEntity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlSecureResolver::GetEntity method. Asigna un URI a un objeto que contiene el recurso real en C++."
type: docs
weight: 200
url: /es/cpp/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity method


Asocia un URI a un objeto que contiene el recurso real.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | El URI que se devuelve de la llamada a [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| rol | String | Actualmente no se usa. |
| ofObjectToReturn | const TypeInfo\& | El tipo de objeto a devolver. La versión actual solo devuelve objetos Stream. |

### ReturnValue

El flujo devuelto al llamar **GetEntity** en el [XmlResolver](../../xmlresolver/) subyacente. Si se especifica un tipo distinto a Stream, el método devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
