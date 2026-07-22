---
title: "System::Uri-klass"
linktitle: "Uri"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Uri-klass. Enhetlig resursidentifierare. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 7000
url: /sv/cpp/system/uri/
---
## Uri class


Enhetlig resursidentifierare. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Uri : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CheckHostName](./checkhostname/)(String) | Bestämmer typen av det angivna värdnamnet. |
| static [CheckSchemeName](./checkschemename/)(const String\&) | Bestämmer om det angivna schemat är giltigt. |
| static [Compare](./compare/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) | Jämför de angivna [Uri](./)-objekten med hjälp av de angivna jämförelsereglerna. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Bestämmer om URI:erna som representeras av det aktuella och det angivna objektet är lika. |
| static [EscapeDataString](./escapedatastring/)(const String\&) | Konverterar en sträng till dess escapade representation. |
| static [EscapeUriString](./escapeuristring/)(const String\&) | Konverterar en URI-sträng till dess escapade representation. |
| static [FromHex](./fromhex/)(char16_t) | Hämtar det decimala värdet av en hexadecimal siffra. |
| [get_AbsolutePath](./get_absolutepath/)() const | Returnerar den absoluta sökvägen för URI:n. |
| [get_AbsoluteUri](./get_absoluteuri/)() const | Returnerar den absoluta URI:n. |
| [get_Authority](./get_authority/)() const | Returnerar värdnamnet och portnumret för en server. |
| [get_DnsSafeHost](./get_dnssafehost/)() const | Returnerar ett oescapat värdnamn. |
| [get_Fragment](./get_fragment/)() const | Returnerar det escapade URI‑fragmentet. |
| [get_Host](./get_host/)() const | Returnerar värdnamnet. |
| [get_HostNameType](./get_hostnametype/)() const | Returnerar värdnamnstypen. |
| [get_IdnHost](./get_idnhost/)() const | Returnerar ett internationellt domännamn för värden. |
| [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Avgör om URI:n som representeras av det aktuella objektet är absolut. |
| [get_IsDefaultPort](./get_isdefaultport/)() const | Avgör om URI:n som representeras av det aktuella objektet har standardport för URI:ns schema. |
| [get_IsFile](./get_isfile/)() const | Avgör om URI:n som representeras av det aktuella objektet är en fil. |
| [get_IsLoopback](./get_isloopback/)() const | Avgör om URI:n som representeras av det aktuella objektet refererar till en lokal värd. |
| [get_IsUnc](./get_isunc/)() const | Avgör om URI:n som representeras av det aktuella objektet är en UNC-sökväg. |
| [get_LocalPath](./get_localpath/)() const | Returnerar operativsystemets representation av filnamnet som refereras av URI:n som representeras av det aktuella objektet. |
| [get_OriginalString](./get_originalstring/)() const | Returnerar URI‑strängen som skickades till konstruktorn när det aktuella objektet skapades. |
| [get_PathAndQuery](./get_pathandquery/)() const | Returnerar den absoluta sökvägen och frågekomponenterna för URI:n som representeras av det aktuella objektet, separerade med ett frågetecken (?). |
| [get_Port](./get_port/)() const | Returnerar portnumret för URI:n som representeras av det aktuella objektet. |
| [get_Query](./get_query/)() const | Returnerar frågeinformationen som ingår i URI:n som representeras av det aktuella objektet. |
| [get_Scheme](./get_scheme/)() const | Returnerar schemat för URI:n som representeras av det aktuella objektet. |
| [get_Segments](./get_segments/)() const | Returnerar en array av strängar som innehåller sökvägssegmenten för URI:n som representeras av det aktuella objektet. |
| [get_UserEscaped](./get_userescaped/)() const | Avgör om URI‑strängen som skickades till konstruktorn för det aktuella objektet var fullständigt escapad. |
| [get_UserInfo](./get_userinfo/)() const | Returnerar ett användarnamn, lösenord och annan användarinformation som är associerad med URI:n som representeras av det aktuella objektet. |
| [GetComponents](./getcomponents/)(UriComponents, UriFormat) const | Returnerar de angivna komponenterna för URI:n som representeras av det aktuella objektet med den angivna escapingen. |
| [GetHashCode](./gethashcode/)() const override | Hämtar hash‑koden för URI:n. |
| [GetLeftPart](./getleftpart/)(UriPartial) | Returnerar den angivna delen av URI:n som representeras av det aktuella objektet. |
| static [HexEscape](./hexescape/)(char16_t) | Returnerar en hexadecimal motsvarighet till det angivna tecknet. |
| static [HexUnescape](./hexunescape/)(const String\&, int32_t\&) | Konverterar den angivna hexadecimala representationen av ett tecken till ett tecken. |
| [IsBaseOf](./isbaseof/)(const SharedPtr\<Uri\>\&) const | Bestämmer om URI:n som representeras av det aktuella [Uri](./)-objektet är en bas för URI:n som representeras av det angivna [Uri](./)-objektet. |
| static [IsHexDigit](./ishexdigit/)(char16_t) | Bestämmer om det angivna tecknet representerar en giltig hexadecimal siffra. |
| static [IsHexEncoding](./ishexencoding/)(const String\&, int32_t) | Bestämmer om ett tecken i den angivna strängen på den angivna positionen är hexadecimalt kodad. |
| [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indikerar om strängen som användes för att konstruera denna [Uri](./) var välformad och inte behöver ytterligare escapning. |
| static [IsWellFormedUriString](./iswellformeduristring/)(const String\&, UriKind) | Bestämmer om den angivna strängen är en välformad URI. |
| [MakeRelative](./makerelative/)(const SharedPtr\<Uri\>\&) | Bestämmer skillnaden mellan två [Uri](./)-instanser. |
| [MakeRelativeUri](./makerelativeuri/)(const SharedPtr\<Uri\>\&) | Bestämmer skillnaden mellan URI:er som representeras av det aktuella och det angivna [Uri](./)-objektet. |
| [ToString](./tostring/)() const override | Returnerar strängrepresentationen av den URI som representeras av det aktuella objektet. |
| static [TryCreate](./trycreate/)(const String\&, UriKind, SharedPtr\<Uri\>\&) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n; ett argument specificerar URI-typen. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) | Skapar ett [Uri](./)-objekt från det angivna [Uri](./)-objektet som representerar bas-URI:n och strängrepresentationen av relativ URI. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) | Skapar ett [Uri](./)-objekt från de angivna bas- och relativa URI:erna. |
| static [UnescapeDataString](./unescapedatastring/)(const String\&) | Avkodar den angivna kodade strängen. |
| [Uri](./uri/)(const String\&) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n. |
| [Uri](./uri/)(const String\&, bool) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n; ett argument specificerar om URI:n ska escapetas. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&, bool) | Skapar ett [Uri](./)-objekt från det angivna [Uri](./)-objektet som representerar bas-URI:n och strängrepresentationen av relativ URI; ett argument specificerar om URI:n ska escapetas. |
| [Uri](./uri/)(const String\&, UriKind) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n; ett argument specificerar URI-typen. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&) | Skapar ett [Uri](./)-objekt från de angivna bas- och relativa URI:erna. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) | Skapar ett [Uri](./)-objekt från de angivna bas- och relativa URI:erna. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Anger tecknen som separerar kommunikationsprotokollschemat från adressdelen av [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Anger att [Uri](./) är en pekare till en fil. |
| static [UriSchemeFtp](./urischemeftp/) | Anger att [Uri](./) nås via File Transfer Protocol. |
| static [UriSchemeGopher](./urischemegopher/) | Anger att [Uri](./) nås via Gopher-protokollet. |
| static [UriSchemeHttp](./urischemehttp/) | Anger att [Uri](./) nås via Hypertext Transfer Protocol. |
| static [UriSchemeHttps](./urischemehttps/) | Anger att [Uri](./) nås via Secure Hypertext Transfer Protocol. |
| static [UriSchemeMailto](./urischememailto/) | Anger att [Uri](./) är en e-postadress och nås via Simple Mail Transport Protocol. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Anger att [Uri](./) nås via NetPipe-schemat som används av [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Anger att [Uri](./) nås via NetTcp-schemat som används av [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Anger att [Uri](./) är en Internet-nyhetsgrupp och nås via Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Anger att [Uri](./) är en Internet-nyhetsgrupp och nås via Network News Transport Protocol. |
## Anmärkningar



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
This code example produces the following output:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
