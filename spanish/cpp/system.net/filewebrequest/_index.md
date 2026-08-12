---
title: "Clase System::Net::FileWebRequest"
linktitle: "FileWebRequest"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::FileWebRequest. Proporciona una implementación de la clase abstracta WebRequest para trabajar con el sistema de archivos. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.net/filewebrequest/
---
## FileWebRequest class


Proporciona una implementación de la clase abstracta [WebRequest](../webrequest/) para trabajar con el sistema de archivos. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class FileWebRequest : public System::Net::WebRequest
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Abort](./abort/)() override | Aborta la solicitud actual. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Inicia una solicitud asíncrona para el recurso. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Espera hasta que la operación asíncrona especificada para obtener un flujo se complete. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Espera hasta que la solicitud asíncrona especificada para el recurso se complete. |
| [FileWebRequest](./filewebrequest/)(System::SharedPtr\<Uri\>) | Construye una nueva instancia. |
| [get_ContentType](./get_contenttype/)() override | Obtiene el tipo MIME de la solicitud. |
| [get_Headers](./get_headers/)() override | Obtiene la colección de los encabezados HTTP. |
| [get_Method](./get_method/)() override | Obtiene el método HTTP. |
| [get_RequestUri](./get_requesturi/)() override | Devuelve el URI de la solicitud. |
| [GetResponse](./getresponse/)() override | Devuelve la respuesta web asociada con la solicitud web actual. |
| [set_ContentType](./set_contenttype/)(String) override | Establece el tipo MIME de la solicitud. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Establece la colección de encabezados HTTP. |
| [set_Method](./set_method/)(String) override | Establece el método HTTP. |
| [set_Timeout](./set_timeout/)(int) override | Información RTTI. |
## Ver también

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
