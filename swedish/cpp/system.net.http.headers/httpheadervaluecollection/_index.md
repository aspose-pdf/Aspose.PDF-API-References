---
title: "System::Net::Http::Headers::HttpHeaderValueCollection klass"
linktitle: "HttpHeaderValueCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::HttpHeaderValueCollection klass. Representerar samlingen av header‑värdena. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.net.http.headers/httpheadervaluecollection/
---
## HttpHeaderValueCollection class


Representerar samlingen av header‑värdena. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename T>class HttpHeaderValueCollection : public System::Collections::Generic::ICollection<T>
```


| Parameter | Beskrivning |
| --- | --- |
| Den | typ av header‑värdena som representeras i samlingen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const T\&) override | Lägger till ett element i samlingen. |
| [Clear](./clear/)() override | Tar bort alla element från samlingen. |
| [Contains](./contains/)(const T\&) const override | Kontrollerar om ett element finns i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Kopierar alla samlingselement till befintliga array‑element. |
| [get_Count](./get_count/)() const override | RTTI-information. |
| [get_IsReadOnly](./get_isreadonly/)() | Hämtar ett värde som indikerar om den aktuella samlingen är skrivskyddad. |
| [get_IsSpecialValueSet](./get_isspecialvalueset/)() | Hämtar ett värde som indikerar om den aktuella samlingen innehåller ett "specialvärde". |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator. |
| [GetHeaderStringWithoutSpecial](./getheaderstringwithoutspecial/)() | Returnerar en strängrepresentation av den aktuella samlingen utan ett "specialvärde". |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>) | Skapar en ny instans. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Skapar en ny instans. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T) | Skapar en ny instans. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Skapar en ny instans. |
| [ParseAdd](./parseadd/)(String) | Analyserar en header‑strängrepresentation och lägger till den i den aktuella samlingen. |
| [Remove](./remove/)(const T\&) override | Tar bort ett element från samlingen. |
| [RemoveSpecialValue](./removespecialvalue/)() | Tar bort ett "specialvärde". |
| [SetSpecialValue](./setspecialvalue/)() | Ställer in ett "specialvärde". |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Ställ in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| [TryParseAdd](./tryparseadd/)(String) | Försöker tolka en rubriksträngsrepresentation och lägga till den i den aktuella samlingen. |

## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
