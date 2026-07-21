---
title: "System::Net::Http::Headers::HttpContentHeaders clase"
linktitle: "HttpContentHeaders"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::HttpContentHeaders clase. Representa la colección de los encabezados ''Content''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.net.http.headers/httpcontentheaders/
---
## HttpContentHeaders class


Representa la colección de los encabezados 'Content'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class HttpContentHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Agrega los encabezados conocidos a la colección especificada. |
| [get_Allow](./get_allow/)() | Información RTTI. |
| [get_ContentDisposition](./get_contentdisposition/)() | Obtiene un valor del encabezado 'Content-Disposition'. |
| [get_ContentEncoding](./get_contentencoding/)() | Obtiene un valor del encabezado 'Content-Encoding'. |
| [get_ContentLanguage](./get_contentlanguage/)() | Obtiene un valor del encabezado 'Content-Language'. |
| [get_ContentLength](./get_contentlength/)() | Obtiene un valor del encabezado 'Content-Length'. |
| [get_ContentLocation](./get_contentlocation/)() | Obtiene un valor del encabezado 'Content-Location'. |
| [get_ContentMD5](./get_contentmd5/)() | Obtiene un valor del encabezado 'Content-MD5'. |
| [get_ContentRange](./get_contentrange/)() | Obtiene un valor del encabezado 'Content-Range'. |
| [get_ContentType](./get_contenttype/)() | Obtiene un valor del encabezado 'Content-Type'. |
| [get_Expires](./get_expires/)() | Obtiene un valor del encabezado 'Expires'. |
| [get_LastModified](./get_lastmodified/)() | Obtiene un valor del encabezado 'Last-Modified'. |
| [HttpContentHeaders](./httpcontentheaders/)(HeaderFunc\<Nullable\<int64_t\>\>) | Construye una nueva instancia. |
| [set_ContentDisposition](./set_contentdisposition/)(System::SharedPtr\<ContentDispositionHeaderValue\>) | Establece un valor del encabezado 'Content-Disposition'. |
| [set_ContentLength](./set_contentlength/)(Nullable\<int64_t\>) | Establece un valor del encabezado 'Content-Length'. |
| [set_ContentLocation](./set_contentlocation/)(System::SharedPtr\<Uri\>) | Establece un valor del encabezado 'Content-Location'. |
| [set_ContentMD5](./set_contentmd5/)(System::ArrayPtr\<uint8_t\>) | Establece un valor del encabezado 'Content-MD5'. |
| [set_ContentRange](./set_contentrange/)(System::SharedPtr\<ContentRangeHeaderValue\>) | Establece un valor del encabezado 'Content-Range'. |
| [set_ContentType](./set_contenttype/)(System::SharedPtr\<MediaTypeHeaderValue\>) | Establece un valor del encabezado 'Content-Type'. |
| [set_Expires](./set_expires/)(Nullable\<DateTimeOffset\>) | Establece un valor del encabezado 'Expires'. |
| [set_LastModified](./set_lastmodified/)(Nullable\<DateTimeOffset\>) | Establece un valor del encabezado 'Last-Modified'. |
## Ver también

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
