---
title: "System::Net::Http::Headers::HttpHeaderValueCollection< System::String > klass"
linktitle: "String >"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::HttpHeaderValueCollection< System::String > klass. Den partiella specialiseringen av HttpHeaderValueCollection‑mallen för String‑typen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.net.http.headers/string_/
---
## String > class


Den partiella specialiseringen av mallen [HttpHeaderValueCollection](../httpheadervaluecollection/) för typen [String](../../system/string/). Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class String > : public System::Collections::Generic::ICollection<System::String>,
                 public System::Collections::Generic::ICollection<System::String>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const String\&) override | Lägger till ett element i samlingen. |
| [Clear](./clear/)() override | Tar bort alla element från samlingen. |
| [Contains](./contains/)(const String\&) const override | Kontrollerar om ett element finns i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<String\>, int32_t) override |  |
| [get_Count](./get_count/)() const override | Hämtar antalet element i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() |  |
| [get_IsSpecialValueSet](./get_isspecialvalueset/)() |  |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator. |
| [GetHeaderStringWithoutSpecial](./getheaderstringwithoutspecial/)() |  |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>) |  |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<String\>\>, String\>) |  |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, String) |  |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, String, Action\<System::SharedPtr\<HttpHeaderValueCollection\<String\>\>, String\>) |  |
| [ParseAdd](./parseadd/)(String) |  |
| [Remove](./remove/)(const String\&) override | Tar bort ett element från samlingen. |
| [RemoveSpecialValue](./removespecialvalue/)() |  |
| [SetSpecialValue](./setspecialvalue/)() |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Ställ in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| [TryParseAdd](./tryparseadd/)(String) |  |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
