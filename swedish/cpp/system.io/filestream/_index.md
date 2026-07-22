---
title: "System::IO::FileStream-klass"
linktitle: "FileStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileStream-klass. Representerar en filström som stödjer synkrona och asynkrona läs- och skrivoperationer. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1500
url: /sv/cpp/system.io/filestream/
---
## FileStream class


Representerar en filström som stödjer synkrona och asynkrona läs- och skrivoperationer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FileStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger det aktuella [FileStream](./)-objektet. |
| [FileStream](./filestream/)(const String\&, FileMode) | Skapar en ny instans av [FileStream](./)-klassen och initierar den med de angivna parametrarna. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) | Skapar en ny instans av [FileStream](./)-klassen och initierar den med de angivna parametrarna. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) | Skapar en ny instans av [FileStream](./)-klassen och initierar den med de angivna parametrarna. |
| [FileStream](./filestream/)(const FileStream\&) |  |
| [Flush](./flush/)() override | Rensar denna ströms buffertar och skriver all buffrad data till den underliggande filen. |
| [Flush](./flush/)(bool) | Rensar denna ströms buffertar och skriver all buffrad data till den underliggande filen. Synonym för metoden [Flush()](./flush/). |
| [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) override | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen är läsbar. |
| [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen är skrivbar. |
| [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| [get_Name](./get_name/)() const | Returnerar namnet på filen som kapslas in av det aktuella [FileStream](./)-objektet. |
| [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| [operator=](./operator=/)(const FileStream\&) |  |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| [ReadByte](./readbyte/)() override | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som är ekvivalent med värdet på den lästa byten. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| [set_Position](./set_position/)(int64_t) override | Spolar strömmen och sätter sedan strömmens position. |
| [SetLength](./setlength/)(int64_t) override | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | Skriver asynkront en sekvens av bytes till den aktuella strömmen, förflyttar den aktuella positionen i strömmen med antalet skrivna bytes och övervakar avbokningsförfrågningar. |
| [WriteByte](./writebyte/)(uint8_t) override | Skriver det angivna osignerade 8-bitars heltalsvärdet till strömmen. |
| [~FileStream](./~filestream/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Standardvärde för antalet byte som buffras under läs- och skrivoperationer. |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |
## Se även

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
