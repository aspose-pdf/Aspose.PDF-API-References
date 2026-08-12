---
title: "Aspose::Pdf::Text::CharInfoCollection klass"
linktitle: "CharInfoCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::CharInfoCollection-klass. Representerar en samling av CharInfo-objekt i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class


Representerar en samling av [CharInfo](../charinfo/) objekt.

```cpp
class CharInfoCollection : public System::Collections::Generic::ICollection<System::SharedPtr<CharInfo>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [Add](./add/)(const System::SharedPtr\<CharInfo\>\&) override | [Collection](../../aspose.pdf/collection/) är skrivskyddad, kastar NotImplementedException |
. |
| [Clear](./clear/)() override | [Collection](../../aspose.pdf/collection/) är skrivskyddad. Kastar alltid NotImplementedException. |
| [Contains](./contains/)(const System::SharedPtr\<CharInfo\>\&) const override | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<CharInfo\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet [CharInfo](../charinfo/) objekt som faktiskt finns i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar [CharInfo](../charinfo/) elementet vid det angivna indexet. |
|  | [Remove](./remove/)(const System::SharedPtr\<CharInfo\>\&) override | [Collection](../../aspose.pdf/collection/) är skrivskyddad, kastar NotImplementedException |
. |
## Anmärkningar


Tillhandahåller åtkomst till positionsinformation för tecken i textsegment.
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
