---
title: "System::Security::Cryptography::CryptoStream klass"
linktitle: "CryptoStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::CryptoStream klass. Strömsimplementation som omsluter en befintlig ström med en kryptografisk funktion. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.security.cryptography/cryptostream/
---
## CryptoStream class


Strömsimplementation som omsluter en befintlig ström med en kryptografisk funktion. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CryptoStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger anslutning. |
| [CryptoStream](./cryptostream/)(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) | Konstruktor. |
| [Flush](./flush/)() override | Tömmer bufferten till den omslutna strömmen. Gör inget eftersom transformalgoritmen kan fortfarande vänta på mer data. |
| [FlushFinalBlock](./flushfinalblock/)() | Skriver data som fortfarande finns i bufferten till strömmen. |
| [get_CanRead](./get_canread/)() const override | Kontrollerar om strömmen är läsbar. |
| [get_CanSeek](./get_canseek/)() const override | Kontrollerar om strömmen är sökbar. |
| [get_CanWrite](./get_canwrite/)() const override | Kontrollerar om strömmen är skrivbar. |
| [get_Length](./get_length/)() const override | Hämtar längden på strömmen. Stöds inte. |
| [get_Position](./get_position/)() const override | Hämtar aktuell position i strömmen. Stöds inte. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Läser data från strömmen. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Läser data från strömmen. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Söker position i strömmen. Stöds inte. |
| [set_Position](./set_position/)(int64_t) override | Söker position i strömmen. Stöds inte. |
| [SetLength](./setlength/)(int64_t) override | Söker storlek på strömmen. Stöds inte. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Skriver data till strömmen. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Skriver data till strömmen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |
## Se även

* Class [Stream](../../system.io/stream/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
