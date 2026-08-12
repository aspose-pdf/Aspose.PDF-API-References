---
title: "System::Net::Http::HttpContent klass"
linktitle: "HttpContent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::HttpContent klass. Representerar innehållet i en HTTP‑entitet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.net.http/httpcontent/
---
## HttpContent class


Representerar innehållet i en HTTP‑entitet. [Object](../../system/object/) av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpContent : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Avslutar den aktuella instansen. Denna metod avslutar också strömmen som returneras av 'ReadAsStream' och minnesbufferten om den har skapats. |
| [get_Headers](./get_headers/)() | Returnerar HTTP‑innehållshuvudena. |
| [LoadIntoBuffer](./loadintobuffer/)() | Serialiserar innehållet till en minnesbuffert. |
| [LoadIntoBuffer](./loadintobuffer/)(int64_t) | Serialiserar innehållet till en minnesbuffert. |
| [ReadAsByteArray](./readasbytearray/)() | Serialiserar innehållet och returnerar en byte‑array. |
| [ReadAsStream](./readasstream/)() | Serialiserar innehållet och returnerar en ström. |
| [ReadAsString](./readasstring/)() | Serialiserar innehållet och returnerar en sträng. |
| virtual [TryComputeLength](./trycomputelength/)(int64_t\&) | Försöker beräkna innehållsstorleken. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultStringEncoding](./defaultstringencoding/) | Standardkodningen. |
| static [MaxBufferSize](./maxbuffersize/) | Det maximala antalet byte. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
