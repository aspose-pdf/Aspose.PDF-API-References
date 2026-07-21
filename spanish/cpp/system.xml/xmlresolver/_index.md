---
title: "Clase System::Xml::XmlResolver"
linktitle: "XmlResolver"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlResolver. Resuelve recursos XML externos nombrados por un Identificador Uniforme de Recursos (URI) en C++."
type: docs
weight: 3500
url: /es/cpp/system.xml/xmlresolver/
---
## XmlResolver class


Resuelve recursos XML externos nombrados mediante un Identificador Uniforme de Recursos (URI).

```cpp
class XmlResolver : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) | Cuando se sobrescribe en una clase derivada, asigna un URI a un objeto que contiene el recurso real. |
| virtual [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) | Cuando se sobrescribe en una clase derivada, resuelve el URI absoluto a partir del URI base y los URIs relativos. |
| virtual [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) | Cuando se sobrescribe en una clase derivada, establece las credenciales usadas para autenticar solicitudes web. |
| virtual [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) | Permite que el resolvedor devuelva tipos distintos a Stream. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
