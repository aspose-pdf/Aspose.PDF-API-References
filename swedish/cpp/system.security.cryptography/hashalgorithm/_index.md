---
title: "System::Security::Cryptography::HashAlgorithm klass"
linktitle: "HashAlgorithm"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::HashAlgorithm klass. Basisklass för hash-algoritmer. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1600
url: /sv/cpp/system.security.cryptography/hashalgorithm/
---
## HashAlgorithm class


Basisklass för hash-algoritmer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HashAlgorithm : public System::Security::Cryptography::ICryptoTransform
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Hashar buffert. |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&, int, int) | Hashar buffertsegment. |
| [ComputeHash](./computehash/)(SharedPtr\<IO::Stream\> const\&) | Läser ström tills slutet och beräknar hash för den lästa datan. |
| static [Create](./create/)(const String\&) | Skapar hash-algoritm baserat på namn. |
| virtual [get_Hash](./get_hash/)() | Hämtar värdet av den beräknade hashkoden. |
| virtual [get_HashSize](./get_hashsize/)() | Hämtar storleken på det beräknade hashvärdet i byte. |
| [get_InputBlockSize](./get_inputblocksize/)() override | Inmatningsblockstorlek. |
| [get_OutputBlockSize](./get_outputblocksize/)() override | Utmatningsblockstorlek. |
| virtual [Initialize](./initialize/)() | Återställer hasharen till ursprungligt tillstånd. |
| [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) override | Bearbetar ett datablok och kopierar data till utmatningsarrayen. |
| [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) override | Bearbetar sista datablok och beräknar hash. |
| virtual [~HashAlgorithm](./~hashalgorithm/)() | Destruktor. |
## Se även

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
