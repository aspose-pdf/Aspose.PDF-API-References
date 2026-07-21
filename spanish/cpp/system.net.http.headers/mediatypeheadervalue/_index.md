---
title: "System::Net::Http::Headers::MediaTypeHeaderValue clase"
linktitle: "MediaTypeHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::MediaTypeHeaderValue clase. Representa un tipo MIME en el valor del encabezado ''Content-Type''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.net.http.headers/mediatypeheadervalue/
---
## MediaTypeHeaderValue class


Representa un tipo MIME en el valor del encabezado 'Content-Type'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class MediaTypeHeaderValue : public virtual System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_CharSet](./get_charset/)() | Información RTTI. |
| [get_MediaType](./get_mediatype/)() | Obtiene un valor del encabezado de tipo de medio. |
| [get_Parameters](./get_parameters/)() | Devuelve los parámetros de valor del encabezado de tipo de medio. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetMediaTypeLength](./getmediatypelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [MediaTypeHeaderValue](./). |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)() | Construye una nueva instancia. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)(String) | Construye una nueva instancia. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [MediaTypeHeaderValue](./). |
| [set_CharSet](./set_charset/)(String) | Establece un conjunto de caracteres. |
| [set_MediaType](./set_mediatype/)(String) | Establece un valor del encabezado de tipo de medio. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [MediaTypeHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
