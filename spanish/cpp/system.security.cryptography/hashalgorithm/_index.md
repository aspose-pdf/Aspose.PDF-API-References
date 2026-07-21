---
title: "System::Security::Cryptography::HashAlgorithm clase"
linktitle: "HashAlgorithm"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::HashAlgorithm clase. Clase base para algoritmos de hash. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1600
url: /es/cpp/system.security.cryptography/hashalgorithm/
---
## HashAlgorithm class


Clase base para algoritmos de hash. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class HashAlgorithm : public System::Security::Cryptography::ICryptoTransform
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Búfer de hashes. |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&, int, int) | Segmento del búfer de hashes. |
| [ComputeHash](./computehash/)(SharedPtr\<IO::Stream\> const\&) | Lee el flujo hasta el final y calcula el hash de los datos leídos. |
| static [Create](./create/)(const String\&) | Crea un algoritmo de hash basado en el nombre. |
| virtual [get_Hash](./get_hash/)() | Obtiene el valor del código hash calculado. |
| virtual [get_HashSize](./get_hashsize/)() | Obtiene el tamaño del valor hash calculado en bytes. |
| [get_InputBlockSize](./get_inputblocksize/)() override | Tamaño del bloque de entrada. |
| [get_OutputBlockSize](./get_outputblocksize/)() override | Tamaño del bloque de salida. |
| virtual [Initialize](./initialize/)() | Restablece el generador de hash al estado inicial. |
| [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) override | Procesa un bloque de datos y copia los datos al arreglo de salida. |
| [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) override | Procesa el último bloque de datos y calcula el hash. |
| virtual [~HashAlgorithm](./~hashalgorithm/)() | Destructor. |
## Ver también

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
