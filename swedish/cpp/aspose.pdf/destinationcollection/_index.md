---
title: "Aspose::Pdf::DestinationCollection klass"
linktitle: "DestinationCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DestinationCollection klass. Klassen representerar samlingen av alla destinationer (ett namnt träd som mappar namnsträngar till destinationer (se 12.3.2.3, \\\"Named Destinations\\\") och (se 7.7.4, \\\"Name Dictionary\\\")) i pdf-dokumentet i C++."
type: docs
weight: 3500
url: /sv/cpp/aspose.pdf/destinationcollection/
---
## DestinationCollection class


Klassen representerar samlingen av alla destinationer (ett namntre som mappar namnsträngar till destinationer (se 12.3.2.3, "Named Destinations") och (se 7.7.4, "Name Dictionary")) i pdf-dokumentet.

```cpp
class DestinationCollection : public System::Collections::Generic::ICollection<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Object>>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Lägger till det angivna objektet. [Collection](../collection/) är skrivskyddad. Kastar alltid NotSupportedException‑undantag. |
| [Clear](./clear/)() override | [Collection](../collection/) är skrivskyddad. Kastar alltid NotSupportedException‑undantag. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) const override | Bestämmer om denna instans innehåller objektet. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\>, int32_t) override | Kopierar elementen i samlingen till en Array, med start vid ett specifikt Array-index. |
| [get_Count](./get_count/)() const override | Hämtar antalet element som finns i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [GetEnumerator](./getenumerator/)() override | Returnerar enumeratorn. |
| [GetExplicitDestination](./getexplicitdestination/)(const System::String\&, bool) | Returnerar den explicita destinationen med namnet. |
| [GetPageNumber](./getpagenumber/)(const System::String\&, bool) | Returnerar sidnumret för destinationen med namnet. |
| [idx_get](./idx_get/)(int32_t) | Hämtar destinationsobjektet efter index. |
| [IndexOf](./indexof/)(System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>) const | Returnerar indexet för destinationen i samlingen. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Tar bort det angivna objektet. [Collection](../collection/) är skrivskyddad. Kastar alltid ett NotSupportedException-undantag. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
