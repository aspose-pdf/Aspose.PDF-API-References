---
title: "Clase System::Net::NetworkCredential"
linktitle: "NetworkCredential"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::NetworkCredential. Proporciona credenciales para los esquemas de autenticación basados en contraseña. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2900
url: /es/cpp/system.net/networkcredential/
---
## NetworkCredential class


Proporciona credenciales para los esquemas de autenticación basados en contraseña. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class NetworkCredential : public System::Net::ICredentials,
                          public System::Net::ICredentialsByHost,
                          public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Domain](./get_domain/)() | Obtiene el dominio que verifica las credenciales. |
| [get_Password](./get_password/)() | Obtiene la contraseña. |
| [get_UserName](./get_username/)() | Información RTTI. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Devuelve credenciales para la URI especificada y el tipo de autenticación. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Devuelve credenciales para el nombre de host, puerto y tipo de autenticación especificados. |
| [NetworkCredential](./networkcredential/)() | Construye una nueva instancia. |
| [NetworkCredential](./networkcredential/)(String, String) | Construye una nueva instancia. |
| [NetworkCredential](./networkcredential/)(String, String, String) | Construye una nueva instancia. |
| [set_Domain](./set_domain/)(String) | Establece el dominio que verifica las credenciales. |
| [set_Password](./set_password/)(String) | Establece la contraseña. |
| [set_UserName](./set_username/)(String) | Establece el nombre de usuario. |
## Ver también

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
