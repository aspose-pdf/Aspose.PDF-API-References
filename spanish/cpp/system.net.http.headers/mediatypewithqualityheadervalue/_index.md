---
title: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue clase"
linktitle: "MediaTypeWithQualityHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue clase. Representa un tipo MIME con un factor de calidad adicional en el valor del encabezado ''Content-Type''. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1300
url: /es/cpp/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue class


Representa un tipo MIME con un factor de calidad adicional en el valor del encabezado 'Content-Type'. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Quality](./get_quality/)() | Información RTTI. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | Construye una nueva instancia. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String) | Construye una nueva instancia. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String, double) | Construye una nueva instancia. |
| static [Parse](./parse/)(String) | Convierte una cadena proporcionada en una instancia de la clase [MediaTypeWithQualityHeaderValue](./). |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Establece un valor de calidad. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeWithQualityHeaderValue\>\&) | Intenta convertir una cadena proporcionada en una instancia de la clase [MediaTypeWithQualityHeaderValue](./). |
## Ver también

* Class [MediaTypeHeaderValue](../mediatypeheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
