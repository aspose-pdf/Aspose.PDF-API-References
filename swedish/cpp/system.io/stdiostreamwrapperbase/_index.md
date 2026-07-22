---
title: "System::IO::STDIOStreamWrapperBase klass"
linktitle: "STDIOStreamWrapperBase"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::STDIOStreamWrapperBase klass. Representerar en basklass för System.IO.Stream-liknande omslag. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2000
url: /sv/cpp/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase class


Representerar en basklass för [System.IO.Stream](../stream/)-liknande omslag. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen stöder läsning. |
| [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| [get_CanWrite](./get_canwrite/)() const override | Bestämmer om strömmen stöder skrivning. |
| [get_Length](./get_length/)() const override | Returnerar strömmens längd. |
| [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| [operator=](./operator=/)(const STDIOStreamWrapperBase\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| [set_Position](./set_position/)(int64_t) override | Ställer in strömmens position. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const STDIOStreamWrapperBase\&) | Kopieringskonstruktor. Borttagen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | RTTI-information. |
| [int_type](./int_type/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## Se även

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
