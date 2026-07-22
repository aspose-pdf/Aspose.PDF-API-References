---
title: "Aspose::Pdf::OptimizedMemoryStream-klass"
linktitle: "OptimizedMemoryStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OptimizedMemoryStream-klass. Definierar en MemoryStream som kan innehålla mer standardkapacitet i C++."
type: docs
weight: 12400
url: /sv/cpp/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class


Definierar en MemoryStream som kan innehålla mer standardkapacitet.

```cpp
class OptimizedMemoryStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Flush](./flush/)() override | Funktionen har överskrivits. |
| [get_BufferSize](./get_buffersize/)() const | Hämtar storleken på de underliggande buffertarna. |
| [get_CanRead](./get_canread/)() const override | När den överskrivs i en avledd klass, hämtar den ett värde som indikerar om den aktuella strömmen stödjer läsning. |
| [get_CanSeek](./get_canseek/)() const override | När den överskrivs i en avledd klass, hämtar den ett värde som indikerar om den aktuella strömmen stödjer sökning. |
| [get_CanWrite](./get_canwrite/)() const override | När den överskrivs i en avledd klass, hämtar den ett värde som indikerar om den aktuella strömmen stödjer skrivning. |
| [get_FreeOnDispose](./get_freeondispose/)() const | Hämtar ett värde som indikerar om de underliggande buffertarna ska frigöras vid disponering. |
| [get_Length](./get_length/)() const override | När den överskrivs i en avledd klass, hämtar den strömmens längd i byte. |
| [get_Position](./get_position/)() const override | När den överskrivs i en avledd klass, hämtar eller anger den positionen i den aktuella strömmen. |
| [OptimizedMemoryStream](./optimizedmemorystream/)() | Initierar en ny instans av klassen [OptimizedMemoryStream](./). |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t, const System::ArrayPtr\<uint8_t\>\&) | Initierar en ny instans av klassen [OptimizedMemoryStream](./) baserat på den angivna bytearrayen. |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t) | Initierar en ny instans av klassen [OptimizedMemoryStream](./). |
| [OptimizedMemoryStream](./optimizedmemorystream/)(const System::ArrayPtr\<uint8_t\>\&) | Initierar en ny instans av klassen [OptimizedMemoryStream](./) baserat på den angivna bytearrayen. |
| [Read](./read/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | När den överskrivs i en avledd klass, läser den en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte. |
| [ReadByte](./readbyte/)() override | Läser en byte från strömmen och förflyttar positionen i strömmen med en byte, eller returnerar -1 om den är i slutet av strömmen. |
| [Seek](./seek/)(int64_t, System::IO::SeekOrigin) override | När den överskrivs i en avledd klass, anger den positionen i den aktuella strömmen. |
| [set_BufferSize](./set_buffersize/)(int32_t) | Anger storleken på de underliggande buffertarna. |
| [set_FreeOnDispose](./set_freeondispose/)(bool) | Anger ett värde som indikerar om de underliggande buffertarna ska frigöras vid disponering. |
| [set_Position](./set_position/)(int64_t) override | När den överskrivs i en avledd klass, hämtar eller anger den positionen i den aktuella strömmen. |
| [SetLength](./setlength/)(int64_t) override | När den överskrivs i en avledd klass, anger den längden på den aktuella strömmen. |
| [ToArray](./toarray/)() | Konverterar den aktuella strömmen till en bytearray. |
| [Write](./write/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | När den överskrivs i en avledd klass, skriver den en sekvens av byte till den aktuella strömmen och förflyttar den aktuella positionen i denna ström med antalet skrivna byte. |
| [WriteByte](./writebyte/)(uint8_t) override | Skriver en byte till den aktuella positionen i strömmen och förflyttar positionen i strömmen med en byte. |
| [WriteTo](./writeto/)(const System::SharedPtr\<System::IO::Stream\>\&) | Skriver till den angivna strömmen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Standardvärde för buffertstorlek i byte. |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |
## Se även

* Class [Stream](../../system.io/stream/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
