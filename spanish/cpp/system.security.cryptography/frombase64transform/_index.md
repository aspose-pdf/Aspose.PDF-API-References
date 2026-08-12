---
title: "System::Security::Cryptography::FromBase64Transform clase"
linktitle: "FromBase64Transform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::FromBase64Transform clase. Convierte la instancia de la clase CryptoStream desde base 64. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1500
url: /es/cpp/system.security.cryptography/frombase64transform/
---
## FromBase64Transform class


Convierte la instancia de la clase [CryptoStream](../cryptostream/) desde base 64. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class FromBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clear](./clear/)() | Libera todos los recursos. |
| [Dispose](./dispose/)() | Libera los recursos del sistema operativo adquiridos por el objeto actual. |
| [FromBase64Transform](./frombase64transform/)() | Constructor. |
| [FromBase64Transform](./frombase64transform/)(FromBase64TransformMode) | Constructor. |
| virtual [get_CanReuseTransform](./get_canreusetransform/)() | Obtiene un valor que indica si la transformación actual puede reutilizarse. |
| [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | Obtiene un valor que indica si se pueden transformar múltiples bloques. |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Tamaño del bloque de entrada. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Tamaño del bloque de salida. |
| [TransformBlock](./transformblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) |  |
| [TransformFinalBlock](./transformfinalblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) |  |
| virtual [~FromBase64Transform](./~frombase64transform/)() | Destructor. |
## Ver también

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
