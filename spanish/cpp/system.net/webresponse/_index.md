---
title: "Clase System::Net::WebResponse"
linktitle: "WebResponse"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::WebResponse. Representa una respuesta web. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 4000
url: /es/cpp/system.net/webresponse/
---
## WebResponse class


Representa una respuesta web. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class WebResponse : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Close](./close/)() | Cierra el flujo de respuesta. |
| [Dispose](./dispose/)() override | No hace nada. |
| virtual [get_ContentLength](./get_contentlength/)() | Información RTTI. |
| virtual [get_ContentType](./get_contenttype/)() | Devuelve el tipo MIME del recurso. |
| virtual [get_Headers](./get_headers/)() | Devuelve la colección de encabezados que están asociados con la respuesta actual. |
| virtual [get_ResponseUri](./get_responseuri/)() | Devuelve el URI del recurso. |
| virtual [get_SupportsHeaders](./get_supportsheaders/)() | Devuelve un valor que indica si la respuesta actual admite encabezados. |
| virtual [GetResponseStream](./getresponsestream/)() | Devuelve el flujo de respuesta. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
