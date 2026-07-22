---
title: "Aspose::Pdf::Facades::PdfXmpMetadata klass"
linktitle: "PdfXmpMetadata"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfXmpMetadata klass. Klass för manipulation av XMP-metadata i C++."
type: docs
weight: 3100
url: /sv/cpp/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class


Klass för manipulation med XMP-metadata.

```cpp
class PdfXmpMetadata : public Aspose::Pdf::Facades::SaveableFacade,
                       public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) | Lägger till värde i XMP-metadata. |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&, const System::String\&, const System::String\&, const System::String\&) | Lägger till ett extensionsfält i metadata. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Lägger till ett nytt element i ordboksobjektet. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Lägger till ett nytt element i ordboksobjektet. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Lägger till ett par med nyckel och värde i ordboken. |
| [Clear](./clear/)() override | Tar bort alla element från objektet. |
| [Contains](./contains/)(const System::String\&) const | Kontrollerar om ordboken innehåller den angivna nyckeln. |
| [Contains](./contains/)(const DefaultMetadataProperties\&) const | Kontrollerar om ordboken innehåller den angivna egenskapen. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Kontrollerar om det angivna nyckel‑värdeparet finns i ordboken. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Bestämmer om denna ordbok innehåller den angivna nyckeln. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Kopiera metadata till en array. |
| [get_Count](./get_count/)() const override | Hämtar antalet objekt i samlingen. |
| [get_ExtensionFields](./get_extensionfields/)() | Hämtar ordboken med extensionsfält. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Returnerar true om samlingen har fast storlek. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Returnerar true om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om samlingen är synkroniserad. |
| [get_Keys](./get_keys/)() const override | Hämtar nycklar från ordboken. |
| [get_Values](./get_values/)() const override | Hämtar samlingen av värden i ordboken. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumeratorobjektet för ordboken. |
| [GetNamespaceURIByPrefix](./getnamespaceuribyprefix/)(const System::String\&) | Hämtar namnrymdens URI efter prefix. |
| [GetPrefixByNamespaceURI](./getprefixbynamespaceuri/)(const System::String\&) | Hämtar prefixet efter namnrymdens URI. |
| [GetXmpMetadata](./getxmpmetadata/)() | Hämta XmpMetadata för den angivna PDF-filen i XML-format. |
| [GetXmpMetadata](./getxmpmetadata/)(const System::String\&) | Hämta en del av XmpMetadata för den angivna PDF-filen enligt ett metanamn. |
| [idx_get](./idx_get/)(const System::String\&) const override | Hämtar värde efter nyckel. |
| [idx_get](./idx_get/)(const DefaultMetadataProperties\&) const | Hämtar värde för XMP-metadata efter nyckel. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Ställer in värde efter nyckel. |
| [idx_set](./idx_set/)(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) | Hämtar värde för XMP-metadata efter nyckel. |
| [PdfXmpMetadata](./pdfxmpmetadata/)() | Konstruktor för [PdfXmpMetadata](./). |
| [PdfXmpMetadata](./pdfxmpmetadata/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfXmpMetadata](./)-objekt baserat på *dokumentet*. |
| [RegisterNamespaceURI](./registernamespaceuri/)(const System::String\&, const System::String\&) | Registrerar namnrymdens URI. |
| [Remove](./remove/)(DefaultMetadataProperties) | Tar bort element med angiven nyckel. |
| [Remove](./remove/)(const System::String\&) override | Tar bort nyckel från ordboken. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Tar bort nyckel/värde-par från samlingen. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Försöker hitta nyckel i ordboken och hämtar värdet om den hittas. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
