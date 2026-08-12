---
title: "Clase System::Web::Services::Protocols::WebClientProtocol"
linktitle: "WebClientProtocol"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Web::Services::Protocols::WebClientProtocol. Esta clase base se utiliza en todos los proxies de cliente de servicios web XML que fueron creados usando ASP.NET. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++."
type: docs
weight: 1100
url: /es/cpp/system.web.services.protocols/webclientprotocol/
---
## WebClientProtocol class


Esta clase base se utiliza en todos los proxies de cliente de servicio XML [Web](../../system.web/) que fueron creados usando ASP.NET. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebClientProtocol : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Abort](./abort/)() | Cancela la solicitud. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() | Obtiene el nombre del grupo de conexión. |
| [get_Credentials](./get_credentials/)() | Obtiene la información de autenticación. |
| [get_PreAuthenticate](./get_preauthenticate/)() | Obtiene un valor que indica si la preautenticación está habilitada. |
| [get_RequestEncoding](./get_requestencoding/)() | Obtiene la codificación que se usa para realizar las solicitudes del cliente. |
| [get_Timeout](./get_timeout/)() | Obtiene el intervalo de tiempo a esperar antes de que la solicitud expire. |
| [get_Uri](./get_uri/)() | Obtiene el URI del servicio XML [Web](../../system.web/). |
| [get_Url](./get_url/)() | Obtiene la URL del servicio XML [Web](../../system.web/). |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Obtiene un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(String) | Establece el nombre del grupo de conexión. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<Net::ICredentials\>) | Establece la información de autenticación. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) | Establece un valor que indica si la preautenticación está habilitada. |
| [set_RequestEncoding](./set_requestencoding/)(System::SharedPtr\<Text::Encoding\>) | Establece la codificación que se usa para realizar las solicitudes del cliente. |
| [set_Timeout](./set_timeout/)(int32_t) | Establece el intervalo de tiempo a esperar antes de que la solicitud expire. |
| [set_Uri](./set_uri/)(System::SharedPtr\<Uri\>) | Establece el URI del servicio XML [Web](../../system.web/). |
| [set_Url](./set_url/)(String) | Establece la URL del servicio XML [Web](../../system.web/). |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Establece un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
