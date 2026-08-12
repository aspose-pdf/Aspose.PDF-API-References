---
title: "Clase System::Net::CredentialCache"
linktitle: "CredentialCache"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::CredentialCache. Proporciona el almacenamiento de credenciales. Los objetos de esta clase solo deben asignarse usando la función `System::MakeObject()` . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero `System::SmartPtr` y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.net/credentialcache/
---
## CredentialCache class


Proporciona el almacenamiento de credenciales. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class CredentialCache : public System::Net::ICredentials,
                        public System::Net::ICredentialsByHost
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) | Agrega las credenciales de red especificadas a la caché. |
| [Add](./add/)(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) | Agrega las credenciales de red especificadas a la caché. |
| [CredentialCache](./credentialcache/)() | Construye una nueva instancia. |
| static [get_DefaultCredentials](./get_defaultcredentials/)() | Información RTTI. |
| static [get_DefaultNetworkCredentials](./get_defaultnetworkcredentials/)() | Devuelve las credenciales de red del usuario o aplicación actual. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Devuelve credenciales para el prefijo URI especificado y el tipo de autenticación. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Devuelve credenciales para el nombre de host, puerto y tipo de autenticación especificados. |
| [Remove](./remove/)(System::SharedPtr\<Uri\>, String) | Elimina credenciales de red para el prefijo URI especificado y el tipo de autenticación. |
| [Remove](./remove/)(String, int32_t, String) | Elimina credenciales de red para el nombre de host, puerto y tipo de autenticación especificados. |
## Ver también

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
