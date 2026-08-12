---
title: "System::Net::Http::HttpClientHandler class"
linktitle: "HttpClientHandler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::HttpClientHandler class. Representa el controlador de mensajes predeterminado utilizado por la clase HttpClient. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++."
type: docs
weight: 300
url: /es/cpp/system.net.http/httpclienthandler/
---
## HttpClientHandler class


Representa el controlador de mensajes predeterminado utilizado por la clase [HttpClient](../httpclient/). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpClientHandler : public System::Net::Http::HttpMessageHandler
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | No hace nada. |
| [get_CookieContainer](./get_cookiecontainer/)() | Obtiene el contenedor de cookies que se utiliza para almacenar las cookies del servidor. |
| [get_Credentials](./get_credentials/)() | Obtiene la información de autenticación. |
| [HttpClientHandler](./httpclienthandler/)() | Información RTTI. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) override | Información RTTI. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Establece el contenedor de cookies que se utiliza para almacenar las cookies del servidor. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Establece la información de autenticación. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Establece la información del proxy. |
| [set_Timeout](./set_timeout/)(int32_t) | Obtiene una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| [set_UseCookies](./set_usecookies/)(bool) | Establece el valor que indica si la instancia actual usa el contenedor de cookies para almacenar las cookies del servidor y si la instancia usa cookies del servidor al enviar solicitudes. |
| [set_UseProxy](./set_useproxy/)(bool) | Establece el valor que indica si la instancia actual usa el proxy para enviar solicitudes. |
## Ver también

* Class [HttpMessageHandler](../httpmessagehandler/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
