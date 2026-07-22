---
title: "System::IO::BufferedStream-klass"
linktitle: "BufferedStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BufferedStream-klass. Lägger till ett buffringslager ovanpå en annan ström. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.io/bufferedstream/
---
## BufferedStream class


Lägger till ett buffringslager ovanpå en annan ström. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class BufferedStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&) | Skapar ett [BufferedStream](./)-objekt som omsluter den angivna strömmen och använder en 4096 byte lång buffer. |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&, int) | Skapar ett [BufferedStream](./)-objekt som omsluter den angivna strömmen och använder en buffer med den angivna storleken. |
| [Flush](./flush/)() override | Skriver innehållet i bufferten till den underliggande strömmen. |
| [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen är läsbar. |
| [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen är skrivbar. |
| [get_Length](./get_length/)() const override | Returnerar längden på strömmen. |
| [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från den underliggande strömmen och skriver dem till den angivna bytearrayen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från den underliggande strömmen och skriver dem till den angivna bytearrayen. |
| [ReadByte](./readbyte/)() override | Läser en enda byte från den underliggande strömmen och returnerar ett 32-bitars heltalsvärde som motsvarar värdet på den lästa byten. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| [set_Position](./set_position/)(int64_t) override | Spolar bufferten till den underliggande strömmen och sätter sedan strömmens position. |
| [SetLength](./setlength/)(int64_t) override | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till den underliggande strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till den underliggande strömmen. |
| [WriteByte](./writebyte/)(uint8_t) override | Skriver det angivna teckenlösa 8-bitars heltalsvärdet till den underliggande strömmen. |
| virtual [~BufferedStream](./~bufferedstream/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |
## Se även

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
