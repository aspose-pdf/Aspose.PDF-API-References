---
title: "Clase System::Web::Services::Protocols::HttpWebClientProtocol"
linktitle: "HttpWebClientProtocol"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Web::Services::Protocols::HttpWebClientProtocol. Esta clase base se utiliza en todos los proxies de cliente de servicios Web XML que usan HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol class


Esta clase base se utiliza en todos los proxies de cliente de servicio XML [Web](../../system.web/) que usan HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CheckForCookies](./checkforcookies/)(System::SharedPtr\<Net::HttpWebResponse\>) | Añade cookies de la solicitud especificada al contenedor interno de cookies. |
| [get_AllowAutoRedirect](./get_allowautoredirect/)() | Obtiene un valor que indica si el cliente sigue las redirecciones del servidor. |
| [get_ClientCertificates](./get_clientcertificates/)() | Devuelve la colección de los certificados del cliente. |
| [get_CookieContainer](./get_cookiecontainer/)() | Obtiene un contenedor que se utiliza para almacenar cookies. |
| [get_EnableDecompression](./get_enabledecompression/)() | Obtiene un valor que indica si la descompresión está habilitada. |
| [get_Proxy](./get_proxy/)() | Obtiene información del proxy. |
| [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Obtiene un valor que indica si el uso compartido de conexiones está habilitado cuando el cliente usa autenticación NTLM. |
| [get_UserAgent](./get_useragent/)() | Obtiene un valor del encabezado 'User-Agent'. |
| [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Establece un valor que indica si el cliente sigue las redirecciones del servidor. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Establece un contenedor que se utiliza para almacenar cookies. |
| [set_EnableDecompression](./set_enabledecompression/)(bool) | Establece un valor que indica si la descompresión está habilitada. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<Net::IWebProxy\>) | Establece información del proxy. |
| [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(bool) | Establece un valor que indica si el uso compartido de conexiones está habilitado cuando el cliente usa autenticación NTLM. |
| [set_UserAgent](./set_useragent/)(String) | Establece un valor del encabezado 'User-Agent'. |
| [UnregisterMapping](./unregistermapping/)(System::SharedPtr\<Object\>) |  |
## Ver también

* Class [WebClientProtocol](../webclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
