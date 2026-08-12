---
title: "System::Net::CookieCollection klass"
linktitle: "CookieCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::CookieCollection klass. Representerar en lista med sorterade kakor. Objekt av denna klass bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.net/cookiecollection/
---
## CookieCollection class


Representerar en lista med sorterade kakor. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class CookieCollection : public System::Collections::Generic::ICollection<System::SharedPtr<System::Net::Cookie>>
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [Stamp](./stamp/) | RTTI-information. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Cookie\>\&) override | Lägger till en cookie i samlingen. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Lägger till kakor från den angivna samlingen till den aktuella. |
| [Clear](./clear/)() override | Tar bort alla kakor från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<Cookie\>\&) const override | Kontrollerar om samlingen innehåller den angivna kakan. |
| [CookieCollection](./cookiecollection/)() | Skapar en ny instans. |
| [get_Count](./get_count/)() const override | Hämtar antalet element i samlingen. |
| [get_IsOtherVersionSeen](./get_isotherversionseen/)() | Returnerar ett värde som indikerar om samlingen innehåller en kaka med en version som inte är lika med [Cookie::MaxSupportedVersion](../cookie/maxsupportedversion/). |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator. |
| [idx_get](./idx_get/)(int32_t) | Returnerar en kaka från cookie-samlingen på det angivna indexet. |
| [idx_get](./idx_get/)(String) | Returnerar en kaka från cookie-samlingen enligt angivet namn. |
| [IndexOf](./indexof/)(System::SharedPtr\<Cookie\>) | Returnerar indexet för den angivna kakan. |
| [InternalAdd](./internaladd/)(System::SharedPtr\<Cookie\>, bool) | Lägger till den angivna kakan i samlingen. |
| [Remove](./remove/)(const System::SharedPtr\<Cookie\>\&) override | Tar bort den angivna kakan från samlingen. |
| [RemoveAt](./removeat/)(int32_t) | Tar bort en kaka på det angivna indexet. |
| [TimeStamp](./timestamp/)(CookieCollection::Stamp) | Uppdaterar tidsstämpeln enligt angivet scenario och returnerar ett nytt värde. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
