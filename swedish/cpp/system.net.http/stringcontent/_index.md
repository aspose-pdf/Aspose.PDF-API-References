---
title: "System::Net::Http::StringContent-klass"
linktitle: "StringContent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::StringContent-klass. Representerar HTTP‑innehåll som en sträng. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.net.http/stringcontent/
---
## StringContent class


Representerar HTTP‑innehåll som en sträng. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StringContent : public System::Net::Http::ByteArrayContent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [StringContent](./stringcontent/)(String) | RTTI-information. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>) | Skapar en ny instans. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>, String) | Skapar en ny instans. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | Standardkodningen. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | Det maximala antalet byte. |
## Se även

* Class [ByteArrayContent](../bytearraycontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
