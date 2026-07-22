---
title: "System::Net::Http::Headers::CacheControlHeaderValue-klass"
linktitle: "CacheControlHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::CacheControlHeaderValue-klass. Representerar ett värde för ''Cache-Control''-huvudet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue class


Representerar ett värde för ''Cache-Control''-huvudet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Skapar en ny instans. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Extensions](./get_extensions/)() | Returnerar samlingen av cache‑extension‑token. |
| [get_MaxAge](./get_maxage/)() | Hämtar maximalt åldersvärde i sekunder som bestämmer den tid under vilken klienten accepterar ett svar. |
| [get_MaxStale](./get_maxstale/)() | Hämtar värdet som bestämmer om klienten kommer att acceptera utgångna svar. |
| [get_MaxStaleLimit](./get_maxstalelimit/)() | Hämtar värdet i sekunder som bestämmer den tid under vilken klienten accepterar utgångna svar. |
| [get_MinFresh](./get_minfresh/)() | Hämtar värdet som bestämmer färskhetslivslängden. |
| [get_MustRevalidate](./get_mustrevalidate/)() | Hämtar värdet som bestämmer om servern kräver omvalidering av en cachepost när den blir föråldrad. |
| [get_NoCache](./get_nocache/)() | RTTI-information. |
| [get_NoCacheHeaders](./get_nocacheheaders/)() | Hämtar samlingen av fältnamn i ''no-cache''-direktivet i ''Cache-Control''-huvudet. |
| [get_NoStore](./get_nostore/)() | Hämtar värdet som bestämmer om en cache inte får lagra någon del av en HTTP-förfrågan eller svar. |
| [get_NoTransform](./get_notransform/)() | Hämtar värdet som bestämmer om en cache eller proxy inte får ändra någon del av entity‑kroppen. |
| [get_OnlyIfCached](./get_onlyifcached/)() | Hämtar värdet som bestämmer om klienten måste använda endast cachade poster. |
| [get_Private](./get_private/)() | Hämtar värdet som bestämmer om HTTP-svarsmeddelandet eller dess del är avsett för en enskild användare och inte får cachas av en delad cache. |
| [get_PrivateHeaders](./get_privateheaders/)() | Hämtar samlingen av fältnamn i 'private'-direktivet i 'Cache-Control'-headern. |
| [get_ProxyRevalidate](./get_proxyrevalidate/)() | Hämtar värdet som bestämmer om servern kräver omvalidering av en cachepost när den blir föråldrad för de delade användaragentscacherna. |
| [get_Public](./get_public/)() | Hämtar värdet som bestämmer om ett HTTP-svar kan cachas av någon cache. |
| [get_SharedMaxAge](./get_sharedmaxage/)() | Hämtar det delade maximala åldervärdet i sekunder som åsidosätter 'max-age'-direktivet i 'Cache-Control'-headern eller 'Expires'-headern för en delad cache. |
| static [GetCacheControlLength](./getcachecontrollength/)(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [CacheControlHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [CacheControlHeaderValue](./). |
| [set_MaxAge](./set_maxage/)(Nullable\<TimeSpan\>) | Ställer in det maximala åldervärdet i sekunder som bestämmer en tidsperiod då klienten kommer att acceptera ett svar. |
| [set_MaxStale](./set_maxstale/)(bool) | Ställer in värdet som bestämmer om klienten kommer att acceptera utgångna svar. |
| [set_MaxStaleLimit](./set_maxstalelimit/)(Nullable\<TimeSpan\>) | Ställer in värdet i sekunder som bestämmer den tid då klienten kommer att acceptera utgångna svar. |
| [set_MinFresh](./set_minfresh/)(Nullable\<TimeSpan\>) | Ställer in värdet som bestämmer färskhetslivslängden. |
| [set_MustRevalidate](./set_mustrevalidate/)(bool) | Ställer in värdet som bestämmer om servern kräver omvalidering av en cachepost när den blir föråldrad. |
| [set_NoCache](./set_nocache/)(bool) | Ställer in värdet som bestämmer om klienten kommer att acceptera ett cachat svar. |
| [set_NoStore](./set_nostore/)(bool) | Ställer in värdet som bestämmer om en cache inte får lagra någon del av en HTTP-förfrågan eller ett svar. |
| [set_NoTransform](./set_notransform/)(bool) | Ställer in värdet som bestämmer om en cache eller proxy inte får ändra någon del av entitetskroppen. |
| [set_OnlyIfCached](./set_onlyifcached/)(bool) | Ställer in värdet som bestämmer om klienten måste använda endast cachade poster. |
| [set_Private](./set_private/)(bool) | Ställer in värdet som bestämmer om HTTP-svarsmeddelandet eller dess del är avsett för en enskild användare och inte får cachas av en delad cache. |
| [set_ProxyRevalidate](./set_proxyrevalidate/)(bool) | Ställer in värdet som bestämmer om servern kräver omvalidering av en cachepost när den blir föråldrad för de delade användaragentscacherna. |
| [set_Public](./set_public/)(bool) | Ställer in värdet som bestämmer om ett HTTP-svar kan cachas av någon cache. |
| [set_SharedMaxAge](./set_sharedmaxage/)(Nullable\<TimeSpan\>) | Ställer in det delade maximala åldervärdet i sekunder som åsidosätter 'max-age'-direktivet i 'Cache-Control'-headern eller 'Expires'-headern för en delad cache. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<CacheControlHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [CacheControlHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
