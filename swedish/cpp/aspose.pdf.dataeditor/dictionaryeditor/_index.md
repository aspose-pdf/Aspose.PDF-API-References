---
title: "Aspose::Pdf::DataEditor::DictionaryEditor‑klass"
linktitle: "DictionaryEditor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DataEditor::DictionaryEditor‑klass. En klass för att komma åt ett dokuments träd‑dictionary (document dictionary, page dictionary, resources dictionary) i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class


En klass för att komma åt ett dokuments träd‑ordbok (dokumentordbok, sidordbok, resursordbok).

```cpp
class DictionaryEditor : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<ICosPdfPrimitive>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<ICosPdfPrimitive\>\&) override | Ställ in [ICosPdfPrimitive](../icospdfprimitive/) till dictionary. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Ställ in [ICosPdfPrimitive](../icospdfprimitive/) till dictionary. |
| [Clear](./clear/)() override | Tar bort alla objekt från [DictionaryEditor](./). |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) const override | Avgör om [DictionaryEditor](./) innehåller ett specifikt värde. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Avgör om [DictionaryEditor](./) innehåller ett element med den specificerade nyckeln. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\>, int32_t) override | Kopierar elementen i [DictionaryEditor](./) till en [Array](../../aspose.pdf/xmpfieldtype/), med start vid ett specifikt [Array](../../aspose.pdf/xmpfieldtype/)‑index. |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Page\>\&) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Document\>\&) | ArgumentNullException |
| [DictionaryEditor](./dictionaryeditor/)(const System::SharedPtr\<Resources\>\&) | ArgumentNullException |
| [get_AllKeys](./get_allkeys/)() const | Fullständig samling av nycklar. Innehåller redigerbara och icke‑redigerbara nycklar. |
| [get_Count](./get_count/)() const override | Hämtar antalet element som finns i [DictionaryEditor](./). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om [DictionaryEditor](./) är skrivskyddad. |
| [get_Keys](./get_keys/)() const override | [Collection](../../aspose.pdf/collection/) av redigerbara nycklar. |
| [get_Values](./get_values/)() const override | Hämtar en [ICollection](../../system.collections.generic/icollection/icollection/) som innehåller värdena i [DictionaryEditor](./). |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom samlingen. |
| [idx_get](./idx_get/)(const System::String\&) const override | Hämtar elementet med den angivna nyckeln. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>) override | Ställer in elementet med den angivna nyckeln. |
| [Remove](./remove/)(const System::String\&) override | Tar bort elementet med den angivna nyckeln från [DictionaryEditor](./). |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<ICosPdfPrimitive\>\>\&) override | Tar bort den första förekomsten av ett specifikt objekt från [DictionaryEditor](./). |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<ICosPdfPrimitive\>\&) const override | För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer. |
## Se även

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::DataEditor](../)
* Library [Aspose.PDF for C++](../../)
