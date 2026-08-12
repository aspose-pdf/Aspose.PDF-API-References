---
title: "System::IO::BinaryReader klass"
linktitle: "BinaryReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BinaryReader klass. Representerar en läsare som läser primitiva datatyper som binär data i en viss kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.io/binaryreader/
---
## BinaryReader class


Representerar en läsare som läser primitiva datatyper som binär data i en viss kodning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class BinaryReader : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&) | Skapar en instans av [BinaryReader](./) klass som läser data från den angivna strömmen med UTF-8-kodning. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Skapar en instans av [BinaryReader](./) klass som läser data från den angivna strömmen med den angivna kodningen. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) | Skapar en instans av [BinaryReader](./) klass som läser data från den angivna strömmen med den angivna kodningen. |
| virtual [Close](./close/)() | Stänger det aktuella [BinaryReader](./) objektet och den underliggande inmatningsströmmen. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual [get_BaseStream](./get_basestream/)() | Returnerar inmatningsströmmen. |
| virtual [PeekChar](./peekchar/)() | Läser ett enda tecken från inmatningsströmmen utan att ändra strömmens läsmarkör. |
| virtual [Read](./read/)() | Läser ett enda tecken från inmatningsströmmen. |
| virtual [Read](./read/)(ArrayPtr\<uint8_t\>, int, int) | Läser det angivna antalet byte från inmatningsströmmen och skriver dem till den angivna bytearrayen. |
| virtual [Read](./read/)(ArrayPtr\<char_t\>, int, int) | Läser det angivna antalet tecken från inmatningsströmmen, konverterar dem till UTF-16-kodning och skriver de resulterande UTF-16-tecknen till den angivna teckenarrayen med början på den angivna positionen. |
| virtual [ReadBoolean](./readboolean/)() | Läser ett enda byte från inmatningsströmmen och returnerar dess booleska representation. |
| virtual [ReadByte](./readbyte/)() | Läser en enda byte från inmatningsströmmen. |
| virtual [ReadBytes](./readbytes/)(int) | Läser det angivna antalet byte från inmatningsströmmen. |
| virtual [ReadChar](./readchar/)() | Läser ett enda tecken från inmatningsströmmen. |
| virtual [ReadChars](./readchars/)(int) | Läser det angivna antalet tecken från inmatningsströmmen och returnerar dem i UTF-16‑kodning. |
| virtual [ReadDecimal](./readdecimal/)() | INTE IMPLEMENTERAD. |
| virtual [ReadDouble](./readdouble/)() | Läser 8 byte från inmatningsströmmen och returnerar dem som ett dubbelprecisionsflyttal. |
| virtual [ReadInt16](./readint16/)() | Läser 2 byte från inmatningsströmmen och returnerar dem som ett 16‑bitars heltal. |
| virtual [ReadInt32](./readint32/)() | Läser 4 byte från inmatningsströmmen och returnerar dem som ett 32‑bitars heltal. |
| virtual [ReadInt64](./readint64/)() | Läser 8 byte från inmatningsströmmen och returnerar dem som ett 64‑bitars heltal. |
| virtual [ReadSByte](./readsbyte/)() | Läser en enda byte från inmatningsströmmen och returnerar den som ett signerat 8‑bitars heltal. |
| virtual [ReadSingle](./readsingle/)() | Läser 4 byte från inmatningsströmmen och returnerar dem som ett enkelprecisionsflyttal. |
| virtual [ReadString](./readstring/)() | Läser en sträng från den aktuella strömmen. Strängen föregås av längden, kodad som ett heltal sju bitar åt gången. |
| virtual [ReadUInt16](./readuint16/)() | Läser 2 byte från inmatningsströmmen och returnerar dem som ett osignerat 16‑bitars heltal. |
| virtual [ReadUInt32](./readuint32/)() | Läser 4 byte från inmatningsströmmen och returnerar dem som ett osignerat 32‑bitars heltal. |
| virtual [ReadUInt64](./readuint64/)() | Läser 8 byte från inmatningsströmmen och returnerar dem som ett osignerat 64‑bitars heltal. |
| virtual [~BinaryReader](./~binaryreader/)() | Destruktor. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
