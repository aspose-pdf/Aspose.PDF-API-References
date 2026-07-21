---
title: "Clase System::Net::HttpWebRequest"
linktitle: "HttpWebRequest"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::HttpWebRequest. Representa la solicitud web HTTP. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.net/httpwebrequest/
---
## HttpWebRequest class


Representa la solicitud web HTTP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Abort](./abort/)() override | Aborta la solicitud actual. |
| virtual [AddRange](./addrange/)(int32_t) | Agrega el encabezado '[Range](../../system/range/)' a la solicitud actual. |
| virtual [AddRange](./addrange/)(System::String, int32_t, int32_t) | Agrega el encabezado '[Range](../../system/range/)' a la solicitud actual. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una solicitud asíncrona para el recurso. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Espera hasta que la operación asíncrona especificada para obtener un flujo se complete. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Espera hasta que la solicitud asíncrona especificada para el recurso se complete. |
| [get_Accept](./get_accept/)() | Obtiene el valor del encabezado HTTP 'Accept'. |
| virtual [get_AllowAutoRedirect](./get_allowautoredirect/)() | Obtiene un valor que indica si la solicitud debe seguir redirecciones. |
| virtual [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Obtiene un valor que indica si los datos recibidos del recurso deben almacenarse en búfer. |
| virtual [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Obtiene un valor que indica si el almacenamiento en búfer está habilitado para enviar datos. |
| virtual [get_ClientCertificates](./get_clientcertificates/)() | Obtiene la colección de certificados que están asociados con la solicitud actual. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() override | Obtiene el nombre del grupo de conexión. |
| [get_ContentLength](./get_contentlength/)() override | Obtiene el número de bytes de los datos de la solicitud que se enviarán. |
| [get_ContentType](./get_contenttype/)() override | Obtiene el tipo MIME de la solicitud. |
| [get_ContinueTimeout](./get_continuetimeout/)() | Obtiene un tiempo de espera para esperar hasta que se reciba el código de estado 100-Continue. |
| virtual [get_CookieContainer](./get_cookiecontainer/)() | Obtiene un contenedor de cookies asociado con la solicitud web actual. |
| [get_Credentials](./get_credentials/)() override | Obtiene la información de autenticación que está asociada con la solicitud actual. |
| virtual [get_HaveResponse](./get_haveresponse/)() | Devuelve un valor que indica si se recibe una respuesta. |
| [get_Headers](./get_headers/)() override | Obtiene la colección de los encabezados HTTP. |
| virtual [get_KeepAlive](./get_keepalive/)() | Obtiene un valor que indica si la solicitud actual debe contener el encabezado 'Keep-Alive'. |
| virtual [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Obtiene el número máximo de redirecciones permitidas. |
| [get_Method](./get_method/)() override | Obtiene el método HTTP. |
| [get_PreAuthenticate](./get_preauthenticate/)() override | Obtiene un valor que indica si la solicitud debe estar preautenticada. |
| [get_Proxy](./get_proxy/)() override | Obtiene el proxy HTTP. |
| virtual [get_Referer](./get_referer/)() | Obtiene un valor del encabezado 'Referer'. |
| [get_RequestUri](./get_requesturi/)() override | Devuelve el URI de la solicitud. |
| virtual [get_SendChunked](./get_sendchunked/)() | Obtiene un valor que indica si los datos deben enviarse en segmentos. |
| [get_ServicePoint](./get_servicepoint/)() | Devuelve un punto de servicio que representa la conexión de red al recurso. |
| virtual [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Devuelve un valor que indica si la solicitud actual puede usar un contenedor de cookies. |
| [get_Timeout](./get_timeout/)() override | Obtiene una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Obtiene un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
| virtual [get_UserAgent](./get_useragent/)() | Obtiene un valor del encabezado 'User-Agent'. |
| [GetRequestStream](./getrequeststream/)() override | Devuelve el flujo para escribir datos en el recurso. |
| [GetResponse](./getresponse/)() override | Devuelve la respuesta web asociada con la solicitud web actual. |
| [HttpWebRequest](./httpwebrequest/)(System::SharedPtr\<Uri\>) | Construye una nueva instancia. |
| [set_Accept](./set_accept/)(String) | Establece el valor del encabezado HTTP 'Accept'. |
| virtual [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Establece un valor que indica si la solicitud debe seguir redirecciones. |
| virtual [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(bool) | Establece un valor que indica si los datos recibidos del recurso deben almacenarse en búfer. |
| virtual [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(bool) | Establece un valor que indica si el almacenamiento en búfer está habilitado para enviar datos. |
| virtual [set_ClientCertificates](./set_clientcertificates/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>) | Establece la colección de certificados que están asociados con la solicitud actual. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) override | Establece el nombre del grupo de conexión. |
| [set_ContentLength](./set_contentlength/)(int64_t) override | Establece el número de bytes de los datos de la solicitud a enviar. |
| [set_ContentType](./set_contenttype/)(String) override | Establece el tipo MIME de la solicitud. |
| [set_ContinueTimeout](./set_continuetimeout/)(int32_t) | Establece un tiempo de espera para esperar hasta que se reciba el código de estado 100-Continue. |
| virtual [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Establece un contenedor de cookies asociado con la solicitud web actual. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) override | Establece la información de autenticación que está asociada con la solicitud actual. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Establece la colección de encabezados HTTP. |
| virtual [set_KeepAlive](./set_keepalive/)(bool) | Establece un valor que indica si la solicitud actual debe contener el encabezado 'Keep-Alive'. |
| virtual [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Establece un número máximo de redirecciones permitidas. |
| [set_Method](./set_method/)(String) override | Establece el método HTTP. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) override | Establece un valor que indica si la solicitud debe estar preautenticada. |
| [set_ProtocolVersion](./set_protocolversion/)(System::Version) | Información RTTI. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) override | Establece el proxy HTTP. |
| virtual [set_Referer](./set_referer/)(System::String) | Establece un valor del encabezado 'Referer'. |
| virtual [set_SendChunked](./set_sendchunked/)(bool) | Establece un valor que indica si los datos deben enviarse en segmentos. |
| [set_Timeout](./set_timeout/)(int) override | Establece una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) override | Establece un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
| virtual [set_UserAgent](./set_useragent/)(System::String) | Establece un valor del encabezado 'User-Agent'. |
## Ver también

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
