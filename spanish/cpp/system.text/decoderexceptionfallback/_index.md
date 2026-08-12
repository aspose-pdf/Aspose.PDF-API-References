---
title: "System::Text::DecoderExceptionFallback clase"
linktitle: "DecoderExceptionFallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::DecoderExceptionFallback clase. Proporciona una estrategia de reserva que lanza excepciones. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.text/decoderexceptionfallback/
---
## DecoderExceptionFallback class


Proporciona una estrategia de reserva que lanza excepciones. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class DecoderExceptionFallback : public System::Text::DecoderFallback
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Crea un búfer de reserva. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Obtiene el recuento máximo de caracteres que la instancia puede devolver. |
## Ver también

* Class [DecoderFallback](../decoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
