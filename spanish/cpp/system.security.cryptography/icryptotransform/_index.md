---
title: "Clase System::Security::Cryptography::ICryptoTransform"
linktitle: "ICryptoTransform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::ICryptoTransform. Clase base del transformador criptográfico. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.security.cryptography/icryptotransform/
---
## ICryptoTransform class


Clase base del transformador criptográfico. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ICryptoTransform : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Tamaño del bloque de entrada. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Tamaño del bloque de salida. |
| virtual [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Información RTTI. |
| virtual [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) | Procesa el último bloque de datos y calcula el valor de salida. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
