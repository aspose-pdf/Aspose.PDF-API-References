---
title: "System::Net::Sockets::NetworkStream class"
linktitle: "NetworkStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::NetworkStream class. Tillhandahåller den underliggande strömmen av data för nätverksåtkomst. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.net.sockets/networkstream/
---
## NetworkStream class


Tillhandahåller den underliggande strömmen av data för nätverksåtkomst. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class NetworkStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron läsoperation. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron skrivoperation. |
| [Close](./close/)(int) | Stänger den aktuella instansen efter att den angivna tiden har löpt ut. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Väntar tills den angivna asynkrona läsoperationen är klar. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen är klar. |
| [Flush](./flush/)() override | Rensar den här strömmens buffertar och skriver all buffrad data till den underliggande lagringen. |
| [get_CanRead](./get_canread/)() const override | RTTI-information. |
| [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| [get_CanTimeout](./get_cantimeout/)() const override | Hämtar ett värde som avgör om den aktuella strömmen kan tidsgränsas. |
| [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen är skrivbar. |
| [get_DataAvailable](./get_dataavailable/)() const | Returnerar ett värde som indikerar om det finns tillgänglig data att läsa. |
| [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| [get_Socket](./get_socket/)() | Hämtar den underliggande [Socket](../socket/). |
| [get_WriteTimeout](./get_writetimeout/)() const override | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka skriva innan tidsgränsen nås. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>) | Skapar en ny instans. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) | Skapar en ny instans. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) | Skapar en ny instans. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| [set_Position](./set_position/)(int64_t) override | Ställer in strömmens position. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Ställer in ett värde som avgör om den aktuella strömmen kan tidsgränsas. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Ställer in ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| [SetLength](./setlength/)(int64_t) override | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| virtual [~NetworkStream](./~networkstream/)() | Förstör den aktuella instansen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |
## Se även

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
