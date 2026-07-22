---
title: "Aspose::Pdf::Annotations::AppearanceDictionary-klass"
linktitle: "AppearanceDictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::AppearanceDictionary-klass. Annotationsutseendedictionary som specificerar hur annotationen ska visas visuellt på sidan i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class


[Annotation](../annotation/) appearance dictionary specifying how the annotation shall be presented visually on the page.

```cpp
class AppearanceDictionary : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XForm>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XForm\>\&) override | Lägg till X-form för angiven nyckel. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Lägger till ett par med nyckel och värde i ordboken. |
| [Clear](./clear/)() override | Tar bort alla element från dictionaryn. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) const override | Kontrollerar om det angivna nyckel‑värdeparet finns i ordboken. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Bestämmer om denna ordbok innehåller den angivna nyckeln. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<XForm\>\>\&, int32_t) | Kopierar elementen i dictionaryn till en Array, med start vid ett specifikt Array-index. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\>, int32_t) override | Kopierar elementen i ICollection till en Array, med start vid ett specifikt Array-index. |
| [get_Count](./get_count/)() const override | Hämtar antalet element som finns i dictionaryn. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Hämtar ett värde som indikerar om dictionaryn har en fast storlek. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om dictionaryn är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till dictionaryn är synkroniserad (trådsäker). |
| [get_Keys](./get_keys/)() const override | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [Keys](../) contains (N | R | D).state‑värden, där N - normalutseende, R - rullningsutseende, D - nedtrycktutseende och state - namnet på tillståndet (t.ex. On, Off för kryssrutor). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till dictionaryn. |
| [get_Values](./get_values/)() const override | Hämtar listan över dictionaryns värden. Resultatsamlingen innehåller listan över [XForm](../../aspose.pdf/xform/)‑objekt. |
| [GetEnumerator](./getenumerator/)() override | Returnerar ett IDictionaryEnumerator‑objekt för dictionaryn. |
| [idx_get](./idx_get/)(const System::String\&) const override | Representerar ett bekvämt sätt att hämta utseendeströmmar. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XForm\>) override | Representerar ett bekvämt sätt att hämta utseendeströmmar. |
| [Remove](./remove/)(const System::String\&) override | Tar bort nyckel från ordboken. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Tar bort nyckel/värde-par från samlingen. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XForm\>\&) const override | Försöker hitta nyckel i ordboken och hämtar värdet om den hittas. |
## Se även

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
