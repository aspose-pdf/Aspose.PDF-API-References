---
title: "System::IO::StreamReader class"
linktitle: "StreamReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StreamReader class. Representerar en läsare som läser tecken från en byte‑ström. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2200
url: /sv/cpp/system.io/streamreader/
---
## StreamReader class


Representerar en läsare som läser tecken från en byte‑ström. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StreamReader : public System::IO::TextReader
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger de aktuella och underliggande strömmarna. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| [get_BaseStream](./get_basestream/)() const | Returnerar en delad pekare till ett objekt som representerar den underliggande strömmen. |
| [get_CurrentEncoding](./get_currentencoding/)() | Returnerar den för närvarande använda kodningen. |
| [get_EndOfStream](./get_endofstream/)() | Returnerar ett värde som indikerar om slutet av strömmen har nåtts. |
| [Peek](./peek/)() override | Läser ett enskilt tecken från strömmen utan att ändra strömmens läsmarkör. |
| [Read](./read/)() override | Läser ett enskilt tecken från strömmen. |
| [Read](./read/)(ArrayPtr\<char_t\>, int, int) override | Läser det angivna antalet tecken från strömmen, konverterar dem till UTF‑16‑kodning och skriver de resulterande UTF‑16‑tecknen till den angivna teckenarrayen med start på den angivna positionen. |
| [ReadLine](./readline/)() override | Läser tecken från strömmen tills slutet av den aktuella raden. |
| [ReadToEnd](./readtoend/)() override | Läser tecken från strömmen tills slutet av strömmen. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna underliggande strömmen med UTF‑8‑kodning och en buffert med standardstorlek på 1024 byte. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, bool) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek på 1024 byte. En parameter anger om detektering av byteordningsmarkör ska vara aktiverad. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med standardstorlek på 1024 byte. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med standardstorlek på 1024 byte. En parameter anger om detektering av byteordningsmarkör ska vara aktiverad. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med den angivna storleken. En parameter anger om detektering av byteordningsmarkör ska vara aktiverad. |
| [StreamReader](./streamreader/)(const System::String\&) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna filen med UTF-8-kodning och en buffert med standardstorlek på 4096 byte. |
| [StreamReader](./streamreader/)(const System::String\&, bool) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna filen med UTF-8-kodning och en buffert med standardstorlek på 4096 byte. En parameter anger om detektering av byteordningsmarkör ska vara aktiverad. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna filen med den angivna kodningen och en buffert med standardstorlek på 4096 byte. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med standardstorlek på 4096 byte. En parameter anger om detektering av byteordningsmarkör ska vara aktiverad. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool, int) | Skapar en instans av [StreamReader](./)-objektet som läser tecken från den angivna filen med den angivna kodningen och en buffert med den angivna storleken. En parameter anger om detektering av byteordningsmarkör ska vara aktiverad. |
| [~StreamReader](./~streamreader/)() | Destruktor. |
## Se även

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
