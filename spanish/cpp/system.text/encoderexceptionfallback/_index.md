---
title: "System::Text::EncoderExceptionFallback clase"
linktitle: "EncoderExceptionFallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::EncoderExceptionFallback clase. Proporciona una estrategia de reserva que lanza excepciones. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.text/encoderexceptionfallback/
---
## EncoderExceptionFallback class


Proporciona una estrategia de reserva que lanza excepciones. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class EncoderExceptionFallback : public System::Text::EncoderFallback
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Crea un búfer de reserva. |
| [EncoderExceptionFallback](./encoderexceptionfallback/)() | Constructor. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Obtiene el recuento máximo de caracteres que la instancia puede devolver. |
## Ver también

* Class [EncoderFallback](../encoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
