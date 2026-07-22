---
title: "Aspose::Pdf::Metadata class"
linktitle: "Metadata"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Metadata class. Tillhandahåller åtkomst till XMP-metadataström i C++."
type: docs
weight: 11200
url: /sv/cpp/aspose.pdf/metadata/
---
## Metadata class


Tillhandahåller åtkomst till XMP-metadataström.

```cpp
class Metadata : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Lägger till värde i metadata. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Lägger till värde i metadata. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Lägger till pdf‑utökning i metadata. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Lägger till ett par med nyckel och värde i ordboken. |
| [Clear](./clear/)() override | Rensar metadata. |
| [Contains](./contains/)(const System::String\&) const | Kontrollerar om nyckeln finns i metadata. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Kontrollerar om det angivna nyckel‑värdeparet finns i ordboken. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Bestämmer om denna ordbok innehåller den angivna nyckeln. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Kopierar element från samlingen till en array. |
| [get_Count](./get_count/)() const override | Hämtar antalet element i samlingen. |
| [get_ExtensionFields](./get_extensionfields/)() | Hämtar ordboken med extensionsfält. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Kontrollerar om samlingen har fast storlek. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Kontrollerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Kontrollerar om samlingen är synkroniserad. |
| [get_Keys](./get_keys/)() const override | Hämtar samling av metadata‑nycklar. |
| [get_NamespaceManager](./get_namespacemanager/)() | Hämtar namnrymdshanterare. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar samlingssynkroniseringsobjektet. |
| [get_Values](./get_values/)() const override | Hämtar värden i metadata. |
| [GetEnumerator](./getenumerator/)() override | Returnerar ordboksenumerator. |
| [GetNamespaceUriByPrefix](./getnamespaceuribyprefix/)(const System::String\&) | Returnerar namnrymdens URI för prefix. |
| [GetPrefixByNamespaceUri](./getprefixbynamespaceuri/)(const System::String\&) | Returnerar prefix för namnrymdens URI. |
| [idx_get](./idx_get/)(const System::String\&) const override | Hämtar data från metadata. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Sätter data från metadata. |
| [RegisterNamespaceUri](./registernamespaceuri/)(const System::String\&, const System::String\&) | Registrerar namnrymdens URI. |
| [RegisterNamespaceUri](./registernamespaceuri/)(const System::String\&, const System::String\&, const System::String\&) | Registrerar namnrymdens URI. |
| [Remove](./remove/)(const System::String\&) override | Tar bort post från metadata. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Tar bort nyckel/värde‑par från samlingen. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Försöker hitta nyckel i ordboken och hämtar värdet om den hittas. |
## Se även

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
