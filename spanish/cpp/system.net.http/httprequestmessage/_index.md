---
title: "System::Net::Http::HttpRequestMessage clase"
linktitle: "HttpRequestMessage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::HttpRequestMessage clase. Representa un mensaje de solicitud HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.net.http/httprequestmessage/
---
## HttpRequestMessage class


Representa un mensaje de solicitud HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpRequestMessage : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Elimina la instancia actual. Este método también elimina el contenido de la solicitud HTTP. |
| [get_Content](./get_content/)() | Obtiene el contenido de la solicitud HTTP. |
| [get_Headers](./get_headers/)() | Devuelve los encabezados de contenido HTTP. |
| [get_Method](./get_method/)() | Obtiene el método de solicitud HTTP. |
| [get_Properties](./get_properties/)() | Devuelve la colección de propiedades de la solicitud HTTP. |
| [get_RequestUri](./get_requesturi/)() | Obtiene el URI del recurso solicitado. |
| [get_Version](./get_version/)() | Información RTTI. |
| [HttpRequestMessage](./httprequestmessage/)() | Construye una nueva instancia. |
| [HttpRequestMessage](./httprequestmessage/)(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) | Construye una nueva instancia. |
| [HttpRequestMessage](./httprequestmessage/)(System::SharedPtr\<HttpMethod\>, String) | Construye una nueva instancia. |
| [MarkAsSent](./markassent/)() | Marca la solicitud actual como enviada. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Establece el contenido de la solicitud HTTP. |
| [set_Method](./set_method/)(System::SharedPtr\<HttpMethod\>) | Establece el método de solicitud HTTP. |
| [set_RequestUri](./set_requesturi/)(System::SharedPtr\<Uri\>) | Establece el URI del recurso solicitado. |
| [set_Version](./set_version/)(System::Version) | Establece la versión HTTP. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
