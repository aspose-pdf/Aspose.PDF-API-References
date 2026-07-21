---
title: "Clase System::Net::WebRequest"
linktitle: "WebRequest"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::WebRequest. Representa una solicitud web. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3800
url: /es/cpp/system.net/webrequest/
---
## WebRequest class


Representa una solicitud web. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class WebRequest : public virtual System::Object
```

## Nested classes

* Class [HttpRequestCreator](./httprequestcreator/)
* Class [WebRequestPrefixElement](./webrequestprefixelement/)
## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Abort](./abort/)() | Aborta la solicitud actual. |
| virtual [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso. |
| virtual [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) | Inicia una solicitud asíncrona para el recurso. |
| static [Create](./create/)(String) | Crea una nueva instancia de la clase [WebRequest](./) usando el URI especificado. |
| static [Create](./create/)(System::SharedPtr\<Uri\>) | Crea una nueva instancia de la clase [WebRequest](./) usando el URI especificado. |
| static [CreateDefault](./createdefault/)(System::SharedPtr\<Uri\>) | Crea un descendiente de [WebRequest](./) para el esquema de URI especificado. |
| static [CreateHttp](./createhttp/)(String) | Crea una nueva instancia de la clase [WebRequest](./) usando el URI especificado. |
| static [CreateHttp](./createhttp/)(System::SharedPtr\<Uri\>) | Crea una nueva instancia de la clase [WebRequest](./) usando el URI especificado. |
| virtual [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación asíncrona especificada para obtener un flujo se complete. |
| virtual [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la solicitud asíncrona especificada para el recurso se complete. |
| virtual [get_CachePolicy](./get_cachepolicy/)() | Obtiene la política de caché. |
| virtual [get_ConnectionGroupName](./get_connectiongroupname/)() | Obtiene el nombre del grupo de conexión. |
| virtual [get_ContentLength](./get_contentlength/)() | Obtiene el número de bytes de los datos de la solicitud que se enviarán. |
| virtual [get_ContentType](./get_contenttype/)() | Obtiene el tipo MIME de la solicitud. |
| virtual [get_Credentials](./get_credentials/)() | Obtiene la información de autenticación que está asociada con la solicitud actual. |
| static [get_DefaultWebProxy](./get_defaultwebproxy/)() | Obtiene el proxy HTTP global. |
| virtual [get_Headers](./get_headers/)() | Obtiene la colección de los encabezados HTTP. |
| virtual [get_Method](./get_method/)() | Obtiene el método HTTP. |
| virtual [get_PreAuthenticate](./get_preauthenticate/)() | Obtiene un valor que indica si la solicitud debe estar preautenticada. |
| static [get_PrefixList](./get_prefixlist/)() | Obtiene la lista de prefijos. |
| virtual [get_Proxy](./get_proxy/)() | Obtiene el proxy HTTP. |
| virtual [get_RequestUri](./get_requesturi/)() | Devuelve el URI de la solicitud. |
| virtual [get_Timeout](./get_timeout/)() | Obtiene una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| virtual [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Obtiene un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
| virtual [GetRequestStream](./getrequeststream/)() | Devuelve el flujo para escribir datos en el recurso. |
| virtual [GetResponse](./getresponse/)() | Devuelve la respuesta web asociada con la solicitud web actual. |
| static [RegisterPrefix](./registerprefix/)(String, System::SharedPtr\<IWebRequestCreate\>) | Registra el descendiente de [WebRequest](./) para el URI especificado. |
| virtual [set_CachePolicy](./set_cachepolicy/)(System::SharedPtr\<System::Net::Cache::RequestCachePolicy\>) | Establece la política de caché. |
| virtual [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) | Establece el nombre del grupo de conexión. |
| virtual [set_ContentLength](./set_contentlength/)(int64_t) | Establece el número de bytes de los datos de la solicitud a enviar. |
| virtual [set_ContentType](./set_contenttype/)(String) | Establece el tipo MIME de la solicitud. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Establece la información de autenticación que está asociada con la solicitud actual. |
| static [set_DefaultWebProxy](./set_defaultwebproxy/)(System::SharedPtr\<IWebProxy\>) | Establece el proxy HTTP global. |
| virtual [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) | Establece la colección de encabezados HTTP. |
| virtual [set_Method](./set_method/)(String) | Establece el método HTTP. |
| virtual [set_PreAuthenticate](./set_preauthenticate/)(bool) | Establece un valor que indica si la solicitud debe estar preautenticada. |
| static [set_PrefixList](./set_prefixlist/)(System::SharedPtr\<Collections::Generic::List\<System::SharedPtr\<WebRequest::WebRequestPrefixElement\>\>\>) | Establece la lista de prefijos. |
| virtual [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Establece el proxy HTTP. |
| virtual [set_Timeout](./set_timeout/)(int32_t) | Establece una cantidad de tiempo en milisegundos después de la cual la solicitud expirará. |
| virtual [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Establece un valor que indica si la propiedad 'Credential' es igual a la propiedad 'DefaultCredentials'. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
