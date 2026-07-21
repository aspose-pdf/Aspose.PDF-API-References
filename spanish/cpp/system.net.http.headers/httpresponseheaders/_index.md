---
title: "Clase System::Net::Http::Headers::HttpResponseHeaders"
linktitle: "HttpResponseHeaders"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::HttpResponseHeaders. Representa la colección de los encabezados ''Response''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.net.http.headers/httpresponseheaders/
---
## HttpResponseHeaders class


Representa la colección de los encabezados 'Response'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpResponseHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Concatena la instancia especificada de HttpHeaders con la actual. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Agrega los encabezados conocidos a la colección especificada. |
| [get_AcceptRanges](./get_acceptranges/)() | Información RTTI. |
| [get_Age](./get_age/)() | Obtiene un valor del encabezado 'Age'. |
| [get_CacheControl](./get_cachecontrol/)() | Obtiene un valor del encabezado 'Cache-Control'. |
| [get_Connection](./get_connection/)() | Devuelve un valor del encabezado 'Connection'. |
| [get_ConnectionClose](./get_connectionclose/)() | Obtiene un valor que indica si el valor del encabezado 'Connection' contiene 'Close'. |
| [get_Date](./get_date/)() | Obtiene un valor del encabezado 'Date'. |
| [get_ETag](./get_etag/)() | Obtiene un valor del encabezado 'ETag'. |
| [get_Location](./get_location/)() | Obtiene un valor del encabezado 'Location'. |
| [get_Pragma](./get_pragma/)() | Devuelve un valor del encabezado 'Pragma'. |
| [get_ProxyAuthenticate](./get_proxyauthenticate/)() | Devuelve un valor del encabezado 'Proxy-Authenticate'. |
| [get_RetryAfter](./get_retryafter/)() | Obtiene un valor del encabezado 'Retry-After'. |
| [get_Server](./get_server/)() | Devuelve un valor del encabezado 'Server'. |
| [get_Trailer](./get_trailer/)() | Devuelve un valor del encabezado 'Trailer'. |
| [get_TransferEncoding](./get_transferencoding/)() | Devuelve un valor del encabezado 'Transfer-Encoding'. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Obtiene un valor que indica si el valor del encabezado 'Transfer-Encoding' contiene 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Devuelve un valor del encabezado 'Upgrade'. |
| [get_Vary](./get_vary/)() | Devuelve un valor del encabezado 'Vary'. |
| [get_Via](./get_via/)() | Devuelve un valor del encabezado 'Via'. |
| [get_Warning](./get_warning/)() | Devuelve un valor del encabezado 'Warning'. |
| [get_WwwAuthenticate](./get_wwwauthenticate/)() | Devuelve un valor del encabezado 'WWW-Authenticate'. |
| [HttpResponseHeaders](./httpresponseheaders/)() | Construye una nueva instancia. |
| [set_Age](./set_age/)(Nullable\<TimeSpan\>) | Establece un valor del encabezado 'Age'. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Establece un valor del encabezado 'Cache-Control'. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Establece un valor que indica si el valor del encabezado 'Connection' contiene 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Establece un valor del encabezado 'Date'. |
| [set_ETag](./set_etag/)(System::SharedPtr\<EntityTagHeaderValue\>) | Establece un valor del encabezado 'ETag'. |
| [set_Location](./set_location/)(System::SharedPtr\<Uri\>) | Establece un valor del encabezado 'Location'. |
| [set_RetryAfter](./set_retryafter/)(System::SharedPtr\<RetryConditionHeaderValue\>) | Establece un valor del encabezado 'Retry-After'. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Establece un valor que indica si el valor del encabezado 'Transfer-Encoding' contiene 'Chunked'. |
## Ver también

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
