---
title: "Aspose::Pdf::DataEditor::CosPdfDictionary klass"
linktitle: "CosPdfDictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DataEditor::CosPdfDictionary klass. En klass för att komma åt ett objekts dictionary i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class


En klass för att komma åt ett objekts ordbok.

```cpp
class CosPdfDictionary : public Aspose::Pdf::DataEditor::CosPdfPrimitive,
                         public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Ställ in [ICosPdfPrimitive](../icospdfprimitive/) till dictionary. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Ställ in [ICosPdfPrimitive](../icospdfprimitive/) till dictionary. |
| [Clear](./clear/)() override | Tar bort alla objekt från [CosPdfDictionary](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Bestämmer om [CosPdfDictionary](./) innehåller ett specifikt värde. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Bestämmer om [CosPdfDictionary](./) innehåller ett element med den angivna nyckeln. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Kopierar elementen i [CosPdfDictionary](./) till en [Array](../../aspose.pdf/xmpfieldtype/), med start vid ett specifikt [Array](../../aspose.pdf/xmpfieldtype/) index. |
| [CosPdfDictionary](./cospdfdictionary/)(const System::SharedPtr\<Resources\>\&) | Skapar ett dictionary från resurser. |
| static [CreateEmptyDictionary](./createemptydictionary/)(const System::SharedPtr\<Page\>\&) | Skapar en tom ordbok som kommer att bifogas till sidan. |
| static [CreateEmptyDictionary](./createemptydictionary/)(const System::SharedPtr\<Document\>\&) | Skapar en tom ordbok som kommer att bifogas till dokumentet. |
| [get_AllKeys](./get_allkeys/)() const | Fullständig samling av nycklar. Innehåller redigerbara och icke‑redigerbara nycklar. |
| [get_Count](./get_count/)() const override | Hämtar antalet element som finns i [CosPdfDictionary](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om [CosPdfDictionary](./) är skrivskyddad. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) av redigerbara nycklar. |
| [get_Values](./get_values/)() const override | Hämtar en [ICollection](../../system.collections.generic/icollection/icollection/) som innehåller värdena i [CosPdfDictionary](./). |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom samlingen. |
| [idx_get](./idx_get/)(const System::String\&) const override | Hämtar elementet med den angivna nyckeln. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Ställer in elementet med den angivna nyckeln. |
| [Remove](./remove/)(const System::String\&) override | Tar bort elementet med den angivna nyckeln från [CosPdfDictionary](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Tar bort den första förekomsten av ett specifikt objekt från [CosPdfDictionary](./). |
| [ToCosPdfDictionary](./tocospdfdictionary/)() override | Försöker kasta detta objekt till [CosPdfDictionary](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer. |
## Se även

* Class [CosPdfPrimitive](../cospdfprimitive/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
