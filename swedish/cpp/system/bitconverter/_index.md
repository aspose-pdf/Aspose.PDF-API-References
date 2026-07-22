---
title: "System::BitConverter-klass"
linktitle: "BitConverter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::BitConverter-klass. Innehåller metoder som utför konverteringar av en sekvens av byte till en värdetyp och vice versa. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 600
url: /sv/cpp/system/bitconverter/
---
## BitConverter class


Innehåller metoder som utför konverteringar av en sekvens av byte till en värdetyp och vice‑versa. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class BitConverter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [_IsLittleEndian](./_islittleendian/)() | Anger endian-ordningen för den aktuella arkitekturen. |
| static [DoubleToInt64Bits](./doubletoint64bits/)(double) | Returnerar ett 64-bitars heltalsvärde vars binära representation är lika med den binära representationen av det angivna dubbelprecisions-flyttalvärdet. |
| static [GetBytes](./getbytes/)(bool) | Konverterar det angivna booleska värdet till en bytearray. |
| static [GetBytes](./getbytes/)(char_t) | Konverterar det angivna char_t-värdet till en bytearray. |
| static [GetBytes](./getbytes/)(int16_t) | Konverterar det angivna 16-bitars heltalsvärdet till en bytearray. |
| static [GetBytes](./getbytes/)(int) | Konverterar det angivna 32-bitars heltalsvärdet till en bytearray. |
| static [GetBytes](./getbytes/)(int64_t) | Konverterar det angivna 64-bitars heltalsvärdet till en bytearray. |
| static [GetBytes](./getbytes/)(uint16_t) | Konverterar det angivna osignerade 16-bitars heltalsvärdet till en bytearray. |
| static [GetBytes](./getbytes/)(uint32_t) | Konverterar det angivna osignerade 32-bitars heltalsvärdet till en bytearray. |
| static [GetBytes](./getbytes/)(uint64_t) | Konverterar det angivna osignerade 64-bitars heltalsvärdet till en bytearray. |
| static [GetBytes](./getbytes/)(float) | Konverterar det angivna enkelprecisions-flyttalvärdet till en bytearray. |
| static [GetBytes](./getbytes/)(double) | Konverterar det angivna dubbelprecisions-flyttalvärdet till en bytearray. |
| static [Int64BitsToDouble](./int64bitstodouble/)(int64_t) | Returnerar ett dubbelprecisions-flyttal vars värde är ekvivalent med värdet. |
| static [ToBoolean](./toboolean/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar en byte från den angivna arrayen med start vid det angivna indexet till ett booleskt värde. |
| static [ToBoolean](./toboolean/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar en byte från den angivna arrayen med start vid det angivna indexet till ett booleskt värde. |
| static [ToChar](./tochar/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar två byte från den angivna arrayen med start vid det angivna indexet till ett char_t‑värde. |
| static [ToChar](./tochar/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar två byte från den angivna arrayen med start vid det angivna indexet till ett char_t‑värde. |
| static [ToDouble](./todouble/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett dubbelprecisionsflyttal. |
| static [ToDouble](./todouble/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett dubbelprecisionsflyttal. |
| static [ToInt16](./toint16/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar två byte från den angivna arrayen med start vid det angivna indexet till ett 16‑bitars heltalsvärde. |
| static [ToInt16](./toint16/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar två byte från den angivna arrayen med start vid det angivna indexet till ett 16‑bitars heltalsvärde. |
| static [ToInt32](./toint32/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett 32‑bitars heltalsvärde. |
| static [ToInt32](./toint32/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett 32‑bitars heltalsvärde. |
| static [ToInt64](./toint64/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett 64‑bitars heltalsvärde. |
| static [ToInt64](./toint64/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett 64‑bitars heltalsvärde. |
| static [ToSingle](./tosingle/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett enkelprecisionsflyttal. |
| static [ToSingle](./tosingle/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett enkelprecisionsflyttal. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, bool, const String\&) | Konverterar alla värden i den angivna byte‑arrayen till deras hexadecimala strängrepresentation. Versal‑/gemener för bokstäver i den hexadecimala notationen samt separatorn som infogas mellan varje par av intilliggande byte anges via motsvarande argument. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, int) | Konverterar värden i den angivna byte‑arrayen till deras hexadecimala strängrepresentation med start vid angivet index. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, int, int) | Konverterar ett intervall av värden i den angivna byte‑arrayen till deras hexadecimala strängrepresentation. |
| static [ToUInt16](./touint16/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar två byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 16‑bitars heltalsvärde. |
| static [ToUInt16](./touint16/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar två byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 16‑bitars heltalsvärde. |
| static [ToUInt32](./touint32/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 32‑bitars heltalsvärde. |
| static [ToUInt32](./touint32/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar fyra byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 32‑bitars heltalsvärde. |
| static [ToUInt64](./touint64/)(const System::ArrayPtr\<uint8_t\>\&, int) | Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 64‑bitars heltalsvärde. |
| static [ToUInt64](./touint64/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Konverterar åtta byte från den angivna arrayen med start vid det angivna indexet till ett osignerat 64‑bitars heltalsvärde. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Anger endianordningen för den aktuella arkitekturen. true om arkitekturen är little endian, false annars. |
## Anmärkningar



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
  // Skapa värden att skriva ut.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Skriv ut värdet och dess byte.
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

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
