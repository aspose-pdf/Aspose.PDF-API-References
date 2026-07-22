---
title: "System::Net::Http::Headers::ContentDispositionHeaderValue klass"
linktitle: "ContentDispositionHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::ContentDispositionHeaderValue klass. Representerar ett värde av ''Content-Disposition''-headern. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue class


Representerar ett värde av 'Content-Disposition'-headern. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Skapar en ny instans. |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)(String) | Skapar en ny instans. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_CreationDate](./get_creationdate/)() | Hämtar filens skapandedatum. |
| [get_DispositionType](./get_dispositiontype/)() | RTTI-information. |
| [get_FileName](./get_filename/)() | Hämtar ett värde som bestämmer hur ett filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheten är fristående och lagras i en separat fil. |
| [get_FileNameStar](./get_filenamestar/)() | Hämtar ett värde som bestämmer hur filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheterna är fristående och lagras i separata filer. |
| [get_ModificationDate](./get_modificationdate/)() | Hämtar filens ändringsdatum. |
| [get_Name](./get_name/)() | Hämtar ett namn för en del av innehållskroppen. |
| [get_Parameters](./get_parameters/)() | Returnerar en parameterkollektion för 'Content-Disposition'-headern. |
| [get_ReadDate](./get_readdate/)() | Hämtar datumet då filen lästes senast. |
| [get_Size](./get_size/)() | Hämtar en ungefärlig filstorlek. |
| static [GetDispositionTypeLength](./getdispositiontypelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [ContentDispositionHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [ContentDispositionHeaderValue](./). |
| [set_CreationDate](./set_creationdate/)(Nullable\<DateTimeOffset\>) | Ställer in filens skapandedatum. |
| [set_DispositionType](./set_dispositiontype/)(String) | Ställer in en dispositionstyp. |
| [set_FileName](./set_filename/)(String) | Ställer in ett värde som bestämmer hur ett filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheten är fristående och lagras i en separat fil. |
| [set_FileNameStar](./set_filenamestar/)(String) | Ställer in ett värde som bestämmer hur filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheterna är fristående och lagras i separata filer. |
| [set_ModificationDate](./set_modificationdate/)(Nullable\<DateTimeOffset\>) | Ställer in filens ändringsdatum. |
| [set_Name](./set_name/)(String) | Ställer in ett namn för en del av innehållskroppen. |
| [set_ReadDate](./set_readdate/)(Nullable\<DateTimeOffset\>) | Ställer in datumet då filen lästes senast. |
| [set_Size](./set_size/)(Nullable\<int64_t\>) | Ställer in en ungefärlig filstorlek. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [ContentDispositionHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
