---
title: "System::Net::Http::HttpClient clase"
linktitle: "HttpClient"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::HttpClient. Representa una clase base de un cliente HTTP para enviar solicitudes y recibir respuestas. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.net.http/httpclient/
---
## HttpClient class


Representa una clase base de un cliente HTTP para enviar solicitudes y recibir respuestas. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CancelPendingRequests](./cancelpendingrequests/)() | Cancela todas las solicitudes pendientes. |
| [get_BaseAddress](./get_baseaddress/)() | Obtiene la dirección base del recurso que se utiliza para enviar solicitudes. |
| [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | Información RTTI. |
| [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | Obtiene el número máximo de bytes del contenido de la respuesta. |
| [get_Timeout](./get_timeout/)() | Obtiene el intervalo de tiempo a esperar antes de que la solicitud expire. |
| [HttpClient](./httpclient/)() | Construye una nueva instancia. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>) | Construye una nueva instancia. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Construye una nueva instancia. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) | Envía la solicitud HTTP especificada. |
| [set_BaseAddress](./set_baseaddress/)(System::SharedPtr\<Uri\>) | Establece la dirección base del recurso que se utiliza para enviar solicitudes. |
| [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(int64_t) | Establece el número máximo de bytes del contenido de la respuesta. |
| [set_Timeout](./set_timeout/)(TimeSpan) | Establece el intervalo de tiempo a esperar antes de que la solicitud expire. |
## Ver también

* Class [HttpMessageInvoker](../httpmessageinvoker/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
