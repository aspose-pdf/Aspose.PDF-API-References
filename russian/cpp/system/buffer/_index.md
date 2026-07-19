---
title: "Класс System::Buffer"
linktitle: "Буфер"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Buffer. Содержит методы, которые манипулируют сырыми массивами байтов. Это статический тип без сервисов экземпляра. Вам никогда не следует создавать его экземпляры какими бы то ни было способами в C++."
type: docs
weight: 1100
url: /ru/cpp/system/buffer/
---
## Buffer class


Содержит методы, манипулирующие необработанными массивами байтов. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры никаким способом.

```cpp
class Buffer
```

## Методы

| Метод | Описание |
| --- | --- |
| static [BlockCopy](./blockcopy/)(const uint8_t *, int, uint8_t *, int, int) | Копирует указанное количество байтов из исходного буфера в целевой буфер. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Интерпретирует два указанных типизированных массива как сырые массивы байтов и копирует данные из одного в другой. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) | Интерпретирует два указанных массива как необработанные массивы байтов и копирует данные из одного в другой. |
| static [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Интерпретирует два указанных типизированных массива как сырые массивы байтов и копирует данные из одного в другой. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Интерпретирует два указанных типизированных массива как сырые массивы байтов и копирует данные из одного в другой. |
| static [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Интерпретирует два указанных типизированных массива как сырые массивы байтов и копирует данные из одного в другой. |
| static [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Интерпретирует два указанных типизированных массива как сырые массивы байтов и копирует данные из одного в другой. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Интерпретирует два указанных типизированных массива как сырые массивы байтов и копирует данные из одного в другой. |
| static [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Интерпретирует два указанных типизированных массива как сырые массивы байтов и копирует данные из одного в другой. |
| static [ByteLength](./bytelength/)(const SharedPtr\<Array\<T\>\>\&) | Определяет количество байтов, занимаемых всеми элементами указанного массива. |
| static [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Определяет количество байтов, занимаемых всеми элементами указанного массива. |
| static [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Определяет количество байтов, занимаемых всеми элементами указанного массива. |
| static [GetByte](./getbyte/)(const SharedPtr\<Array\<T\>\>\&, int) | Интерпретирует указанный типизированный массив как необработанный массив байтов и получает значение байта по указанному смещению. |
| static [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Интерпретирует указанный типизированный массив как необработанный массив байтов и получает значение байта по указанному смещению. |
| static [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Интерпретирует указанный типизированный массив как необработанный массив байтов и получает значение байта по указанному смещению. |
| static [SetByte](./setbyte/)(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) | Интерпретирует указанный типизированный массив как необработанный массив байтов и устанавливает указанное значение байта по указанному смещению. |
| static [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, uint8_t) | Интерпретирует указанный типизированный массив как необработанный массив байтов и устанавливает указанное значение байта по указанному смещению. |
| static [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, uint8_t) | Интерпретирует указанный типизированный массив как необработанный массив байтов и устанавливает указанное значение байта по указанному смещению. |
## Примечания



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
  // Создайте и заполните массив.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Выведите элементы массива.
  Print(first, SIZE);

  // Создайте массив, содержащий часть первого.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Выведите элементы второго массива.
  Print(second, SIZE / 2);

  // Установите значение элемента с индексом 0 и выведите элементы массива.
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

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
