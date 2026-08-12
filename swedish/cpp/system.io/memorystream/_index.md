---
title: "System::IO::MemoryStream-klass"
linktitle: "MemoryStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::MemoryStream-klass. Representerar en ström som läser från och skriver till minnet. Objekt av denna klass bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1800
url: /sv/cpp/system.io/memorystream/
---
## MemoryStream class


Representerar en ström som läser från och skriver till minnet. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class MemoryStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger strömmen. |
| [Flush](./flush/)() override | Gör ingenting. |
| [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen är läsbar. |
| [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen är skrivbar. |
| [get_Capacity](./get_capacity/)() | Returnerar den aktuella kapaciteten för den underliggande minnesbufferten. |
| [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| virtual [GetBuffer](./getbuffer/)() | Returnerar en pekare till den underliggande bufferten. |
| [MemoryStream](./memorystream/)() | Skapar en ny instans av klassen [MemoryStream](./) med initial kapacitet lika med 0. |
| [MemoryStream](./memorystream/)(int) | Skapar en ny instans av klassen [MemoryStream](./) som representerar en ström baserad på en minnesbuffert av angiven storlek. |
| [MemoryStream](./memorystream/)(const ArrayPtr\<uint8_t\>\&, bool) | Skapar en ny instans av klassen [MemoryStream](./) som representerar en minnesström som är ansluten till den angivna minnesbufferten. En parameter anger om strömmen är skrivbar. |
| [MemoryStream](./memorystream/)(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) | Skapar en ny instans av klassen [MemoryStream](./) som representerar en minnesström som är ansluten till ett segment av den angivna minnesbufferten, med start vid det angivna indexet och inkluderande det angivna antalet element. Parametrar anger om strömmen är skrivbar och om metoden GetBytes() kan anropas. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [ReadByte](./readbyte/)() override | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som är ekvivalent med värdet på den lästa byten. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| [set_Capacity](./set_capacity/)(int) | Ställer in kapaciteten för den underliggande minnesbufferten. |
| [set_Position](./set_position/)(int64_t) override | Ställer in strömmens position. |
| [SetLength](./setlength/)(int64_t) override | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| virtual [ToArray](./toarray/)() | Returnerar en kopia av den underliggande minnesbufferten som en byte-array. |
| [TryGetBuffer](./trygetbuffer/)(ArraySegment\<uint8_t\>\&) | Returnerar arrayen av osignerade byte som denna ström skapades från. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [WriteByte](./writebyte/)(uint8_t) override | Skriver det angivna osignerade 8-bitars heltalsvärdet till strömmen. |
| virtual [WriteTo](./writeto/)(SharedPtr\<Stream\>) | Skriver innehållet i den underliggande bufferten till den angivna strömmen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till sig själv. |
## Se även

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
