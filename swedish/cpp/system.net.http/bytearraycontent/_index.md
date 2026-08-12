---
title: "System::Net::Http::ByteArrayContent class"
linktitle: "ByteArrayContent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::ByteArrayContent-klass. Representerar HTTP-innehåll som en byte-array. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.net.http/bytearraycontent/
---
## ByteArrayContent class


Representerar HTTP-innehåll som en byte-array. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ByteArrayContent : public System::Net::Http::HttpContent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>) | RTTI-information. |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) | Skapar en ny instans. |
| [TryComputeLength](./trycomputelength/)(int64_t\&) override | Försöker beräkna byte-arrayens längd. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | Standardkodningen. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | Det maximala antalet byte. |
## Se även

* Class [HttpContent](../httpcontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
