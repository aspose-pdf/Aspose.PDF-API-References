---
title: "Clase System::Net::Http::Headers::HttpRequestHeaders"
linktitle: "HttpRequestHeaders"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::HttpRequestHeaders. Representa la colección de los encabezados ''Request''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.net.http.headers/httprequestheaders/
---
## HttpRequestHeaders class


Representa la colección de los encabezados 'Request'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class HttpRequestHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Concatena la instancia especificada de HttpHeaders con la actual. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Agrega los encabezados conocidos a la colección especificada. |
| [get_Accept](./get_accept/)() | Información RTTI. |
| [get_AcceptCharset](./get_acceptcharset/)() | Devuelve un valor del encabezado 'Accept-Charset'. |
| [get_AcceptEncoding](./get_acceptencoding/)() | Devuelve un valor del encabezado 'Accept-Encoding'. |
| [get_AcceptLanguage](./get_acceptlanguage/)() | Devuelve un valor del encabezado 'Accept-Language'. |
| [get_Authorization](./get_authorization/)() | Obtiene un valor del encabezado 'Authorization'. |
| [get_CacheControl](./get_cachecontrol/)() | Obtiene un valor del encabezado 'Cache-Control'. |
| [get_Connection](./get_connection/)() | Devuelve un valor del encabezado 'Connection'. |
| [get_ConnectionClose](./get_connectionclose/)() | Obtiene un valor que indica si el valor del encabezado 'Connection' contiene 'Close'. |
| [get_Date](./get_date/)() | Obtiene un valor del encabezado 'Date'. |
| [get_Expect](./get_expect/)() | Devuelve el valor del encabezado 'Expect'. |
| [get_ExpectContinue](./get_expectcontinue/)() | Obtiene un valor que indica si el valor del encabezado 'Expect' contiene 'Continue'. |
| [get_From](./get_from/)() | Obtiene un valor del encabezado 'From'. |
| [get_Host](./get_host/)() | Obtiene un valor del encabezado 'Host'. |
| [get_IfMatch](./get_ifmatch/)() | Devuelve un valor del encabezado 'If-Match'. |
| [get_IfModifiedSince](./get_ifmodifiedsince/)() | Obtiene un valor del encabezado 'If-Modified-Since'. |
| [get_IfNoneMatch](./get_ifnonematch/)() | Devuelve un valor del encabezado 'If-None-Match'. |
| [get_IfRange](./get_ifrange/)() | Obtiene un valor del encabezado 'If-Range'. |
| [get_IfUnmodifiedSince](./get_ifunmodifiedsince/)() | Obtiene un valor del encabezado 'If-Unmodified-Since'. |
| [get_MaxForwards](./get_maxforwards/)() | Obtiene un valor del encabezado 'Max-Forwards'. |
| [get_Pragma](./get_pragma/)() | Devuelve un valor del encabezado 'Pragma'. |
| [get_ProxyAuthorization](./get_proxyauthorization/)() | Obtiene un valor del encabezado 'Proxy-Authorization'. |
| [get_Range](./get_range/)() | Obtiene un valor del encabezado '[Range](../../system/range/)' . |
| [get_Referrer](./get_referrer/)() | Obtiene un valor del encabezado 'Referer'. |
| [get_TE](./get_te/)() | Devuelve un valor del encabezado 'TE'. |
| [get_Trailer](./get_trailer/)() | Devuelve un valor del encabezado 'Trailer'. |
| [get_TransferEncoding](./get_transferencoding/)() | Devuelve un valor del encabezado 'Transfer-Encoding'. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Obtiene un valor que indica si el valor del encabezado 'Transfer-Encoding' contiene 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Devuelve un valor del encabezado 'Upgrade'. |
| [get_UserAgent](./get_useragent/)() | Devuelve un valor del encabezado 'User-Agent'. |
| [get_Via](./get_via/)() | Devuelve un valor del encabezado 'Via'. |
| [get_Warning](./get_warning/)() | Devuelve un valor del encabezado 'Warning'. |
| [HttpRequestHeaders](./httprequestheaders/)() | Construye una nueva instancia. |
| [set_Authorization](./set_authorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Establece un valor del encabezado 'Authorization'. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Establece un valor del encabezado 'Cache-Control'. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Establece un valor que indica si el valor del encabezado 'Connection' contiene 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Establece un valor del encabezado 'Date'. |
| [set_ExpectContinue](./set_expectcontinue/)(Nullable\<bool\>) | Establece un valor que indica si el valor del encabezado 'Expect' contiene 'Continue'. |
| [set_From](./set_from/)(String) | Establece un valor del encabezado 'From'. |
| [set_Host](./set_host/)(String) | Establece un valor del encabezado 'Host'. |
| [set_IfModifiedSince](./set_ifmodifiedsince/)(Nullable\<DateTimeOffset\>) | Establece un valor del encabezado 'If-Modified-Since'. |
| [set_IfRange](./set_ifrange/)(System::SharedPtr\<RangeConditionHeaderValue\>) | Establece un valor del encabezado 'If-Range'. |
| [set_IfUnmodifiedSince](./set_ifunmodifiedsince/)(Nullable\<DateTimeOffset\>) | Establece un valor del encabezado 'If-Unmodified-Since'. |
| [set_MaxForwards](./set_maxforwards/)(Nullable\<int32_t\>) | Establece un valor del encabezado 'Max-Forwards'. |
| [set_ProxyAuthorization](./set_proxyauthorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Establece un valor del encabezado 'Proxy-Authorization'. |
| [set_Range](./set_range/)(System::SharedPtr\<RangeHeaderValue\>) | Establece un valor del encabezado '[Range](../../system/range/)'. |
| [set_Referrer](./set_referrer/)(System::SharedPtr\<Uri\>) | Establece un valor del encabezado 'Referer'. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Establece un valor que indica si el valor del encabezado 'Transfer-Encoding' contiene 'Chunked'. |
## Ver también

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
