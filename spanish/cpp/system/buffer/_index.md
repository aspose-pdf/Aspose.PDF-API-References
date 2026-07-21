---
title: "Clase System::Buffer"
linktitle: "Buffer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Buffer. Contiene métodos que manipulan matrices de bytes crudos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de ella por ningún medio en C++."
type: docs
weight: 1100
url: /es/cpp/system/buffer/
---
## Buffer class


Contiene métodos que manipulan arreglos de bytes sin procesar. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Buffer
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [BlockCopy](./blockcopy/)(const uint8_t *, int, uint8_t *, int, int) | Copia un número especificado de bytes del búfer de origen al búfer de destino. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) | Interpreta dos matrices especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra. |
| static [ByteLength](./bytelength/)(const SharedPtr\<Array\<T\>\>\&) | Determina el número de bytes ocupados por todos los elementos de la matriz especificada. |
| static [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Determina el número de bytes ocupados por todos los elementos de la matriz especificada. |
| static [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Determina el número de bytes ocupados por todos los elementos de la matriz especificada. |
| static [GetByte](./getbyte/)(const SharedPtr\<Array\<T\>\>\&, int) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado. |
| static [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado. |
| static [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado. |
| static [SetByte](./setbyte/)(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado. |
| static [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, uint8_t) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado. |
| static [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, uint8_t) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado. |
## Observaciones



```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Crea y llena la matriz.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Imprime los elementos de la matriz.
  Print(first, SIZE);

  // Crea una matriz que contiene una parte de la primera.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Imprime los elementos de la segunda matriz.
  Print(second, SIZE / 2);

  // Establece el valor del elemento en el índice 0 e imprime los elementos de la matriz.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
This code example produces the following output:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
