---
title: "System::IO::BasicSTDIOStreamWrapper klass"
linktitle: "BasicSTDIOStreamWrapper"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BasicSTDIOStreamWrapper-klass. Representerar en System.IO.Stream-liknande omslag för std::basic_iostream och dess avledda objekt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.io/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper class


Representerar ett [System.IO.Stream](../stream/)-liknande omslag för std::basic_iostream och dess avledda objekt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) | Skapar en ny instans av [BasicSTDIOStreamWrapper](./). |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const BasicSTDIOStreamWrapper\&) | Kopieringskonstruktor. Borttagen. |
| [Flush](./flush/)() override | Rensar den här strömmens buffertar och skriver all buffrad data till den underliggande lagringen. |
| [operator=](./operator=/)(const BasicSTDIOStreamWrapper\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Om omslagsläget är binärt läses det angivna antalet bytes från strömmen, annars läses det angivna antalet tecken och konverteras till uint8_t-typ. Skriver resultatet av läsningen till den angivna byte-arrayen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [ReadByte](./readbyte/)() override | Om omslagsläget är binärt läses en enda byte från den senast avkodade teckenlagringen, annars läses ett enda tecken från strömmen och konverteras till uint8_t-typ. |
| [SetLength](./setlength/)(int64_t) override | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Om omslagsläget är binärt skrivs det angivna delintervallet av byte från den angivna bytearrayen till strömmen, annars konverteras det angivna delintervallet av byte från den angivna bytearrayen till [char_type](./char_type/)‑typen och sedan skrivs resultatet till strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [WriteByte](./writebyte/)(uint8_t) override | Om omslagsläget är binärt skrivs det angivna teckenlösa 8-bitars heltalsvärdet till strömmen, annars konverteras det till [char_type](./char_type/)‑typen och sedan skrivs resultatet till strömmen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | RTTI-information. |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## Se även

* Class [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* Class [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
