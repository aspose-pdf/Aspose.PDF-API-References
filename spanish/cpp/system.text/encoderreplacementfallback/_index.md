---
title: "Clase System::Text::EncoderReplacementFallback"
linktitle: "EncoderReplacementFallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::EncoderReplacementFallback. Proporciona una estrategia de reserva que reemplaza el símbolo erróneo con un marcador. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.text/encoderreplacementfallback/
---
## EncoderReplacementFallback class


Proporciona una estrategia de reserva que reemplaza el símbolo erróneo con un sustituto. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class EncoderReplacementFallback : public System::Text::EncoderFallback
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Crea un búfer de reserva. |
| [EncoderReplacementFallback](./encoderreplacementfallback/)() | Constructor que usa la cadena de reemplazo predeterminada "?". |
| [EncoderReplacementFallback](./encoderreplacementfallback/)(const String\&) | Constructor. |
| [get_DefaultString](./get_defaultstring/)() const | Obtiene la cadena de reemplazo. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Obtiene el recuento máximo de caracteres que la instancia puede devolver. |
## Ver también

* Class [EncoderFallback](../encoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
