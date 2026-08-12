---
title: "Clase System::IO::BinaryWriter"
linktitle: "BinaryWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::BinaryWriter. Representa un escritor que escribe valores de tipos primitivos en un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.io/binarywriter/
---
## BinaryWriter class


Representa un escritor que escribe valores de tipos primitivos en un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class BinaryWriter : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BinaryWriter](./binarywriter/)(const StreamPtr\&, const EncodingPtr\&, bool) | Construye una instancia de la clase [BinaryWriter](./) que escribe datos en el flujo especificado usando la codificación especificada. |
| [Close](./close/)() | Cierra el objeto [BinaryWriter](./) actual y el flujo de salida subyacente. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| [Flush](./flush/)() | Vacía el flujo de salida. |
| [get_BaseStream](./get_basestream/)() | Devuelve el flujo de salida. |
| [Seek](./seek/)(int, System::IO::SeekOrigin) | Establece la posición del flujo representado por el objeto actual. |
| virtual [Write](./write/)(uint8_t) | Escribe el valor entero sin signo de 8 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int, int) | Escribe el subrango especificado de bytes del arreglo de bytes especificado en el flujo de salida. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&, int, int) | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado en el flujo de salida. |
| virtual [Write](./write/)(bool) | Escribe un solo byte con valor 0 si **value** es 'true' y 1 si **value** es 'false' en el flujo de salida. |
| virtual [Write](./write/)(char16_t) | Escribe el valor de carácter ancho de 16 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(int16_t) | Escribe el valor entero de 16 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(int) | Escribe el valor entero de 32 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(int64_t) | Escribe el valor entero de 64 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(uint16_t) | Escribe el valor entero sin signo de 16 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(uint32_t) | Escribe el valor entero sin signo de 32 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(uint64_t) | Escribe el valor entero sin signo de 64 bits especificado en el flujo de salida. |
| virtual [Write](./write/)(float) | Escribe el valor de punto flotante de precisión simple especificado en el flujo de salida. |
| virtual [Write](./write/)(double) | Escribe el valor de punto flotante de doble precisión especificado en el flujo de salida. |
| virtual [Write](./write/)(const Decimal\&) | Escribe la representación en bytes del valor [Decimal](../../system/decimal/) especificado en el flujo de salida. |
| virtual [Write](./write/)(const String\&) | Escribe una cadena con prefijo de longitud en la codificación actual al flujo de salida. |
| virtual [Write](./write/)(const char_t *) | Escribe una cadena con prefijo de longitud en la codificación actual al flujo de salida. |
| [~BinaryWriter](./~binarywriter/)() | Destructor. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
