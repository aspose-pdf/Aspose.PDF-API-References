---
title: "System::IO::StreamWriter-klass"
linktitle: "StreamWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StreamWriter-klass. Representerar en skrivare som skriver tecken till en byte‑ström. Objekt av denna klass bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2300
url: /sv/cpp/system.io/streamwriter/
---
## StreamWriter class


Representerar en skrivare som skriver tecken till en byte‑ström. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger strömmen och frigör förvärvade resurser. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| [Flush](./flush/)() override | Spolar innehållet i bufferten till den underliggande strömmen och spolar sedan den underliggande strömmen. |
| [get_AutoFlush](./get_autoflush/)() const | Returnerar ett värde som indikerar om [StreamWriter](./) kommer att spola data till den underliggande strömmen varje gång metoden [StreamWriter::Write](./write/) anropas. |
| [get_BaseStream](./get_basestream/)() const | Returnerar en delad pekare till ett objekt som representerar den underliggande strömmen. |
| [get_Encoding](./get_encoding/)() override | Returnerar den för närvarande använda kodningen. |
| [set_AutoFlush](./set_autoflush/)(bool) | Returnerar ett värde som specificerar om [StreamWriter](./) ska spola data till den underliggande strömmen varje gång metoden [StreamWriter::Write](./write/) anropas. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna underliggande strömmen med UTF-8‑kodning och en buffer med standardstorlek på 1024 byte. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna underliggande strömmen med den angivna kodningen och en buffer med standardstorlek på 1024 byte. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna underliggande strömmen med den angivna kodningen och en buffer av den angivna storleken. En parameter anger om den underliggande strömmen ska stängas när [StreamWriter](./)-objektet avyttras. |
| [StreamWriter](./streamwriter/)(const String\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna filen med UTF-8‑kodning och en buffer med standardstorlek på 1024 byte. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna filen med den angivna kodningen och en buffer med standardstorlek på 1024 byte. En parameter anger om data ska läggas till i filen eller om filen ska skrivas över. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&, int) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna filen med den angivna kodningen och buffertstorleken. En parameter anger om data ska läggas till i filen eller om filen ska skrivas över. |
| [Write](./write/)(char_t) override | Skriver det angivna tecknet till strömmen. |
| [Write](./write/)(const String\&) override | Skriver den angivna strängen till strömmen. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Skriver strängrepresentationen av det angivna objektet till strömmen. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Skriver alla tecken från den angivna arrayen till strömmen. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av UTF-16‑tecken från den angivna teckenarrayen till strömmen. |
| [Write](./write/)(const char_t *) override | Skriver den angivna c‑strängen till strömmen. |
| [Write](./write/)(const System::SharedPtr\<T\>\&) | Skriver strängrepresentationen av det angivna objektet till strömmen. |
| [WriteLine](./writeline/)() override | Skriver radavslutningstecken till strömmen. |
| [WriteLine](./writeline/)(const String\&) override | Skriver den angivna strängen följt av radavslutningstecknen till strömmen. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Skriver strängrepresentationen av det angivna objektet följt av radavslutningstecknen till strömmen. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Skriver alla tecken från den angivna arrayen följt av radavslutningstecknen till strömmen. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen följt av radavslutningstecknen till strömmen. |
| [WriteLine](./writeline/)(const char_t *) override | Skriver den angivna c-strängen följt av radavslutningstecknen till strömmen. |
| [WriteLine](./writeline/)(const System::SharedPtr\<T\>\&) | Skriver strängrepresentationen av det angivna objektet följt av radavslutningstecknen till strömmen. |
| [~StreamWriter](./~streamwriter/)() | Destruktor. |
## Se även

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
