---
title: "Clase System::BitConverter"
linktitle: "BitConverter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::BitConverter. Contiene métodos que realizan conversiones de secuencias de bytes a un tipo de valor y viceversa. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio en C++."
type: docs
weight: 600
url: /es/cpp/system/bitconverter/
---
## BitConverter class


Contiene métodos que realizan conversiones de secuencias de bytes a un tipo de valor y viceversa. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class BitConverter
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [_IsLittleEndian](./_islittleendian/)() | Indica el endianness de la arquitectura actual. |
| static [DoubleToInt64Bits](./doubletoint64bits/)(double) | Devuelve un valor entero de 64 bits cuya representación binaria es igual a la representación binaria del valor de punto flotante de doble precisión especificado. |
| static [GetBytes](./getbytes/)(bool) | Convierte el valor booleano especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(char_t) | Convierte el valor char_t especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(int16_t) | Convierte el valor entero de 16 bits especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(int) | Convierte el valor entero de 32 bits especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(int64_t) | Convierte el valor entero de 64 bits especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(uint16_t) | Convierte el valor entero sin signo de 16 bits especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(uint32_t) | Convierte el valor entero sin signo de 32 bits especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(uint64_t) | Convierte el valor entero sin signo de 64 bits especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(float) | Convierte el valor de punto flotante de precisión simple especificado en una matriz de bytes. |
| static [GetBytes](./getbytes/)(double) | Convierte el valor de punto flotante de doble precisión especificado en una matriz de bytes. |
| static [Int64BitsToDouble](./int64bitstodouble/)(int64_t) | Devuelve un valor de punto flotante de doble precisión cuyo valor es equivalente a value. |
| static [ToBoolean](./toboolean/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte un byte del arreglo especificado a partir del índice especificado en un valor booleano. |
| static [ToBoolean](./toboolean/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte un byte del arreglo especificado a partir del índice especificado en un valor booleano. |
| static [ToChar](./tochar/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado en un valor char_t. |
| static [ToChar](./tochar/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado en un valor char_t. |
| static [ToDouble](./todouble/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado en un valor de punto flotante de doble precisión. |
| static [ToDouble](./todouble/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado en un valor de punto flotante de doble precisión. |
| static [ToInt16](./toint16/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado en un valor entero de 16 bits. |
| static [ToInt16](./toint16/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado en un valor entero de 16 bits. |
| static [ToInt32](./toint32/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado en un valor entero de 32 bits. |
| static [ToInt32](./toint32/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado en un valor entero de 32 bits. |
| static [ToInt64](./toint64/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado en un valor entero de 64 bits. |
| static [ToInt64](./toint64/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado en un valor entero de 64 bits. |
| static [ToSingle](./tosingle/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado en un valor de punto flotante de precisión simple. |
| static [ToSingle](./tosingle/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado en un valor de punto flotante de precisión simple. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, bool, const String\&) | Convierte todos los valores del arreglo de bytes especificado en su representación de cadena hexadecimal. El caso de las letras a usar en la notación hexadecimal y el separador insertado entre cada par de bytes contiguos se especifican mediante los argumentos correspondientes. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, int) | Convierte los valores del arreglo de bytes especificado en su representación de cadena hexadecimal a partir del índice especificado. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, int, int) | Convierte un rango de valores del arreglo de bytes especificado en su representación de cadena hexadecimal. |
| static [ToUInt16](./touint16/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado en un valor entero sin signo de 16 bits. |
| static [ToUInt16](./touint16/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado en un valor entero sin signo de 16 bits. |
| static [ToUInt32](./touint32/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado en un valor entero sin signo de 32 bits. |
| static [ToUInt32](./touint32/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado en un valor entero sin signo de 32 bits. |
| static [ToUInt64](./touint64/)(const System::ArrayPtr\<uint8_t\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado en un valor entero sin signo de 64 bits. |
| static [ToUInt64](./touint64/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado en un valor entero sin signo de 64 bits. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indica el endianness de la arquitectura actual. true si la arquitectura es little endian, false en caso contrario. |
## Observaciones



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Crea valores para imprimir.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Imprime el valor y sus bytes.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
This code example produces the following output:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
