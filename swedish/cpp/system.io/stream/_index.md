---
title: "System::IO::Stream klass"
linktitle: "Stream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Stream klass. En basklass för en mängd olika strömsimplementationer. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2100
url: /sv/cpp/system.io/stream/
---
## Stream class


En basklass för en mängd olika strömsimplementationer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Stream : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Initierar en asynkron läsoperation. |
| virtual [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Initierar en asynkron skrivoperation. |
| virtual [Close](./close/)() | Stänger strömmen. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&) | Kopierar byte till den angivna strömmen. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&, int32_t) | Kopierar byte till den angivna strömmen, med den angivna buffertstorleken. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| virtual [EndRead](./endread/)(System::SharedPtr\<System::IAsyncResult\>) | Väntar tills den angivna asynkrona läsoperationen är klar. |
| virtual [EndWrite](./endwrite/)(System::SharedPtr\<System::IAsyncResult\>) | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen är klar. |
| virtual [Flush](./flush/)() | Rensar den här strömmens buffertar och skriver all buffrad data till den underliggande lagringen. |
| virtual [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| [FlushAsync](./flushasync/)() | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| virtual [get_CanRead](./get_canread/)() const | Bestämmer om strömmen är läsbar. |
| virtual [get_CanSeek](./get_canseek/)() const | Avgör om strömmen stöder sökning. |
| virtual [get_CanTimeout](./get_cantimeout/)() const | Hämtar ett värde som avgör om den aktuella strömmen kan tidsgränsas. |
| virtual [get_CanWrite](./get_canwrite/)() const | Avgör om strömmen är skrivbar. |
| virtual [get_Length](./get_length/)() const | Returnerar strömmens längd i byte. |
| virtual [get_Position](./get_position/)() const | Returnerar strömmens aktuella position. |
| virtual [get_ReadTimeout](./get_readtimeout/)() const | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| virtual [get_WriteTimeout](./get_writetimeout/)() const | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka skriva innan tidsgränsen nås. |
| virtual [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| virtual [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Read](./read/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| virtual [Read](./read/)(const System::Span\<uint8_t\>\&) | Läser det angivna antalet byte från strömmen och skriver dem till det angivna byte‑spannet. |
| virtual [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| virtual [ReadByte](./readbyte/)() | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som är ekvivalent med värdet på den lästa byten. |
| virtual [Seek](./seek/)(int64_t, SeekOrigin) | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| virtual [set_Position](./set_position/)(int64_t) | Ställer in strömmens position. |
| virtual [set_ReadTimeout](./set_readtimeout/)(int) | Ställer in ett värde som avgör om den aktuella strömmen kan tidsgränsas. |
| virtual [set_WriteTimeout](./set_writetimeout/)(int) | Ställer in ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| virtual [SetLength](./setlength/)(int64_t) | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| virtual [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [Write](./write/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| virtual [Write](./write/)(const System::ReadOnlySpan\<uint8_t\>\&) | Skriver det angivna delintervallet av bytes från det angivna byte-området till strömmen. |
| virtual [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | Skriver asynkront en sekvens av bytes till den aktuella strömmen, förflyttar den aktuella positionen i strömmen med antalet skrivna bytes och övervakar avbokningsförfrågningar. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Skriver asynkront en sekvens av bytes till den aktuella strömmen, förflyttar den aktuella positionen i strömmen med antalet skrivna bytes och övervakar avbokningsförfrågningar. |
| virtual [WriteByte](./writebyte/)(uint8_t) | Skriver det angivna osignerade 8-bitars heltalsvärdet till strömmen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](./null/) | En ström utan underliggande lagring. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till denna klass. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
