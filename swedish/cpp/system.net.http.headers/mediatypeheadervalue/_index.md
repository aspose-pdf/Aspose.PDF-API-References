---
title: "System::Net::Http::Headers::MediaTypeHeaderValue klass"
linktitle: "MediaTypeHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::MediaTypeHeaderValue-klass. Representerar en MIME-typ i värdet av ''Content-Type''-rubriken. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.net.http.headers/mediatypeheadervalue/
---
## MediaTypeHeaderValue class


Representerar en MIME-typ i värdet av 'Content-Type'-rubriken. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class MediaTypeHeaderValue : public virtual System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_CharSet](./get_charset/)() | RTTI-information. |
| [get_MediaType](./get_mediatype/)() | Hämtar ett värde för media-typ-rubriken. |
| [get_Parameters](./get_parameters/)() | Returnerar värdeparametrarna för media-typ-rubriken. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetMediaTypeLength](./getmediatypelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [MediaTypeHeaderValue](./). |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)() | Skapar en ny instans. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)(String) | Skapar en ny instans. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [MediaTypeHeaderValue](./). |
| [set_CharSet](./set_charset/)(String) | Ställer in en teckenuppsättning. |
| [set_MediaType](./set_mediatype/)(String) | Ställer in ett värde för media-typ-rubriken. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [MediaTypeHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
