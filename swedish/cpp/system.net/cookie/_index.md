---
title: "System::Net::Cookie-klass"
linktitle: "Cookie"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Cookie-klass. Representerar en HTTP-cookie. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.net/cookie/
---
## Cookie class


Representerar en HTTP-cookie. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekaren och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Cookie : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() | Skapar en kopia av den aktuella instansen. |
| [Cookie](./cookie/)() | Skapar en ny instans. |
| [Cookie](./cookie/)(String, String) | Skapar en ny instans. |
| [Cookie](./cookie/)(String, String, String) | Skapar en ny instans. |
| [Cookie](./cookie/)(String, String, String, String) | Skapar en ny instans. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Comment](./get_comment/)() const | Hämtar värdet för attributet 'Comment'. |
| [get_CommentUri](./get_commenturi/)() const | Hämtar värdet för attributet 'CommentURL'. |
| [get_Discard](./get_discard/)() const | Hämtar värdet för attributet 'Discard'. |
| [get_Domain](./get_domain/)() const | Hämtar värdet för attributet 'Domain'. |
| [get_DomainImplicit](./get_domainimplicit/)() | Hämtar ett värde som indikerar om domänen är implicit. |
| [get_DomainKey](./get_domainkey/)() const | Returnerar domännyckeln. |
| [get_Expired](./get_expired/)() | Hämtar ett värde som indikerar om cookien har gått ut. |
| [get_Expires](./get_expires/)() | Hämtar värdet för attributet 'Expires'. |
| [get_HttpOnly](./get_httponly/)() const | Hämtar värdet för attributet 'HttpOnly'. |
| [get_Name](./get_name/)() const | Hämtar cookiens namn. |
| [get_Path](./get_path/)() const | Hämtar värdet för attributet 'Path'. |
| [get_Plain](./get_plain/)() const | Returnerar ett värde som indikerar om cookie-specifikationen är 'Plain'. |
| [get_Port](./get_port/)() const | Hämtar värdet för attributet 'Port'. |
| [get_PortList](./get_portlist/)() const | Returnerar samlingen av värdena för attributet 'Port'. |
| [get_Secure](./get_secure/)() const | Hämtar värdet för attributet 'Secure'. |
| [get_TimeStamp](./get_timestamp/)() const | Returnerar tiden då cookien skapades. |
| [get_Value](./get_value/)() const | Hämtar cookiens värde. |
| [get_Variant](./get_variant/)() const | Hämtar cookiens specifikation. |
| [get_Version](./get_version/)() const | Hämtar värdet för attributet '[Version](../../system/version/)' |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [InternalSetName](./internalsetname/)(String) | Denna metod anropas av andra metoder för att sätta ett metodnamn. |
| [set_Comment](./set_comment/)(String) | Sätter värdet för attributet 'Comment'. |
| [set_CommentUri](./set_commenturi/)(System::SharedPtr\<Uri\>) | Sätter värdet för attributet 'CommentURL'. |
| [set_Discard](./set_discard/)(bool) | Sätter värdet för attributet 'Discard'. |
| [set_Domain](./set_domain/)(String) | Sätter värdet för attributet 'Domain'. |
| [set_DomainImplicit](./set_domainimplicit/)(bool) | Sätter ett värde som indikerar om domänen är implicit. |
| [set_Expired](./set_expired/)(bool) | Sätter ett värde som indikerar om cookien har gått ut. |
| [set_Expires](./set_expires/)(DateTime) | Sätter värdet för attributet 'Expires'. |
| [set_HttpOnly](./set_httponly/)(bool) | Sätter värdet för attributet 'HttpOnly'. |
| [set_Name](./set_name/)(String) | Sätter cookiens namn. |
| [set_Path](./set_path/)(String) | Sätter värdet för attributet 'Path'. |
| [set_Port](./set_port/)(String) | Sätter värdet för attributet 'Port'. |
| [set_Secure](./set_secure/)(bool) | Sätter värdet för attributet 'Secure'. |
| [set_Value](./set_value/)(String) | Sätter cookiens värde. |
| [set_Variant](./set_variant/)(CookieVariant) | Sätter cookiens specifikation. |
| [set_Version](./set_version/)(int32_t) | Sätter värdet för attributet '[Version](../../system/version/)' |
| [ToServerString](./toserverstring/)() | Serialiserar den aktuella instansen till dess strängrepresentation. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| [VerifySetDefaults](./verifysetdefaults/)(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) | Verifierar och sätter standardattributens värden. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Namnet på attributet 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Namnet på attributet 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Namnet på attributet 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Namnet på attributet 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Separatorn som används för att separera namn och värde för ett attribut. |
| static [ExpiresAttributeName](./expiresattributename/) | Namnet på attributet 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Den 'HttpOnly' attributets namn. |
| static [MaxAgeAttributeName](./maxageattributename/) | Den 'Max-Age' attributets namn. |
| static [MaxSupportedVersion](./maxsupportedversion/) | RTTI-information. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Strängrepresentationen av den maximalt stödda versionen. |
| static [PathAttributeName](./pathattributename/) | Den 'Path' attributets namn. |
| static [PortAttributeName](./portattributename/) | Den 'Port' attributets namn. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Arrayen som innehåller avgränsare för 'Port' attributets värden. |
| static [QuotesLiteral](./quotesliteral/) | Symbolen som används för att omsluta attributets delar. |
| static [ReservedToName](./reservedtoname/) | Ett värde som är reserverat för kakans namn. |
| static [ReservedToValue](./reservedtovalue/) | Ett värde som är reserverat för kakans värde. |
| static [SecureAttributeName](./secureattributename/) | Den 'Secure' attributets namn. |
| static [SeparatorLiteral](./separatorliteral/) | Attributseparatorn. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Prefixet för de speciella attributens namn. |
| static [VersionAttributeName](./versionattributename/) | Den '[Version](../../system/version/)' attributets namn. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
