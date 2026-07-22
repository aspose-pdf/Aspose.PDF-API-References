---
title: "System::Buffer-klass"
linktitle: "Buffer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Buffer-klass. Innehåller metoder som manipulerar råa byte-arrayer. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 1100
url: /sv/cpp/system/buffer/
---
## Buffer class


Innehåller metoder som manipulerar råa byte‑arrayer. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Buffer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [BlockCopy](./blockcopy/)(const uint8_t *, int, uint8_t *, int, int) | Kopierar ett angivet antal byte från källbufferten till destinationsbufferten. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Tolkar två angivna typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) | Tolkar två angivna arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Tolkar två angivna typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Tolkar två angivna typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Tolkar två angivna typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Tolkar två angivna typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [BlockCopy](./blockcopy/)(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Tolkar två angivna typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) | Tolkar två angivna typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static [ByteLength](./bytelength/)(const SharedPtr\<Array\<T\>\>\&) | Bestämmer antalet byte som upptas av alla element i den angivna arrayen. |
| static [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Bestämmer antalet byte som upptas av alla element i den angivna arrayen. |
| static [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Bestämmer antalet byte som upptas av alla element i den angivna arrayen. |
| static [GetByte](./getbyte/)(const SharedPtr\<Array\<T\>\>\&, int) | Tolkar den angivna typade arrayen som en rå byte-array och hämtar bytevärdet vid den angivna byteoffseten. |
| static [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Tolkar den angivna typade arrayen som en rå byte-array och hämtar bytevärdet vid den angivna byteoffseten. |
| static [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Tolkar den angivna typade arrayen som en rå byte-array och hämtar bytevärdet vid den angivna byteoffseten. |
| static [SetByte](./setbyte/)(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) | Tolkar den angivna typade arrayen som en rå byte-array och sätter det angivna bytevärdet vid den angivna byteoffseten. |
| static [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, uint8_t) | Tolkar den angivna typade arrayen som en rå byte-array och sätter det angivna bytevärdet vid den angivna byteoffseten. |
| static [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, uint8_t) | Tolkar den angivna typade arrayen som en rå byte-array och sätter det angivna bytevärdet vid den angivna byteoffseten. |
## Anmärkningar



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
  // Skapa och fyll arrayen.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Skriv ut arrayens element.
  Print(first, SIZE);

  // Skapa en array som innehåller en del av den första.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Skriv ut elementen i den andra arrayen.
  Print(second, SIZE / 2);

  // Sätt värdet på elementet vid index 0 och skriv ut arrayens element.
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

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
