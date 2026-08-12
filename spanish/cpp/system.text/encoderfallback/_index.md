---
title: "Clase System::Text::EncoderFallback"
linktitle: "EncoderFallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::EncoderFallback. Proporciona una API de reserva para manejar errores de codificación. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.text/encoderfallback/
---
## EncoderFallback class


Proporciona una API de reserva para manejar errores de codificación. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class EncoderFallback : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CreateFallbackBuffer](./createfallbackbuffer/)() | Obtiene el búfer asociado al algoritmo de reserva. |
| static [get_ExceptionFallback](./get_exceptionfallback/)() | Obtiene la implementación predeterminada de reserva de excepción. |
| virtual [get_MaxCharCount](./get_maxcharcount/)() const | Obtiene el número máximo de caracteres que puede devolver la reserva. |
| static [get_ReplacementFallback](./get_replacementfallback/)() | Obtiene la implementación predeterminada de reserva de sustitución. |
| static [get_StandardSafeFallback](./get_standardsafefallback/)() | Obtiene la implementación predeterminada estándar segura de reserva. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
