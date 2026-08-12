---
title: "Aspose::Pdf::ImagePlacementCollection klass"
linktitle: "ImagePlacementCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ImagePlacementCollection klass. Representerar en samling av bildplaceringar i C++."
type: docs
weight: 8200
url: /sv/cpp/aspose.pdf/imageplacementcollection/
---
## ImagePlacementCollection class


Representerar en samling av bildplaceringar.

```cpp
class ImagePlacementCollection : public System::Collections::Generic::ICollection<System::SharedPtr<ImagePlacement>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<ImagePlacement\>\&) override | Lägger till textfragment‑elementet på det angivna indexet. |
| [Clear](./clear/)() override | Rensar alla objekt från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<ImagePlacement\>\&) const override | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<ImagePlacement\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet [ImagePlacement](../imageplacement/) objekt som faktiskt finns i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar textfragment‑elementet på det angivna indexet. |
| [Remove](./remove/)(const System::SharedPtr\<ImagePlacement\>\&) override | Tar bort angivet objekt från samlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
