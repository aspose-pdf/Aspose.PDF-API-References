---
title: "Aspose::Pdf::PageCollection klass"
linktitle: "PageCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageCollection-klass. Samling av PDF-dokumentets sidor i C++."
type: docs
weight: 13200
url: /sv/cpp/aspose.pdf/pagecollection/
---
## PageCollection class


[Collection](../collection/) of PDF document pages.

```cpp
class PageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Page>>,
                       public Aspose::Pdf::ISupportsMemoryCleanup
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<Annotations::AnnotationSelector\>\&) | Accepterar [AnnotationSelector](../) besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| [Accept](./accept/)(const System::SharedPtr\<ImagePlacementAbsorber\>\&) | Accepterar [ImagePlacementAbsorber](../imageplacementabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| [Accept](./accept/)(const System::SharedPtr\<Text::TextFragmentAbsorber\>\&) | Accepterar [TextFragmentAbsorber](../) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Accept](./accept/)(const System::SharedPtr\<Text::TextAbsorber\>\&) | Accepterar [TextAbsorber](../) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Add](./add/)() | Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar väljs storleken på den mest förekommande sidan. Om det bara finns två olika sidor används storleken på den första sidan. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) | Lägger till alla sidor från listan i samlingen. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) | Lägger till alla sidor från arrayen i samlingen. |
| [BeginUpdate](./beginupdate/)() | Uppdaterar när gruppändringar påbörjas. Stoppar omberäkning av sidcache vid varje operation. Vi rekommenderar att anropa BeginUpdate/EndUpdate-metoderna i ett try-finally-block. |
| [Clear](./clear/)() override | Rensa sidssamlingen. |
| [Contains](./contains/)(const System::SharedPtr\<Page\>\&) const override | Bestämmer om denna instans innehåller objektet. |
| [CopyPage](./copypage/)(const System::SharedPtr\<Page\>\&) | Lägger till sidan i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Page\>\>, int32_t) override | Kopierar sidor till dokumentet. |
| [Delete](./delete/)(int32_t) | Ta bort angiven sida. |
| [Delete](./delete/)() | Tar bort alla sidor från samlingen. |
| [Delete](./delete/)(const System::ArrayPtr\<int32_t\>\&) | Ta bort sidor vars nummer anges i arrayen. |
| [EndUpdate](./endupdate/)() | Uppdaterar när gruppändringar är slutförda. Återställer omberäkning av sidcache vid varje operation. Vi rekommenderar att anropa BeginUpdate/EndUpdate-metoderna i ett try-finally-block. |
| [Flatten](./flatten/)() | Tar bort alla fält som finns på sidorna och placerar deras värden istället. |
| [FreeMemory](./freememory/)() override | Rensar cachelagrad data. |
| [get_Count](./get_count/)() const override | Hämtar antalet sidor i dokumentet. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar värdet som indikerar om samlingen är skrivskyddad. Returnerar alltid falskt. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om objektet är synkroniserat. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar synkroniseringsobjektet för samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för sidorna. |
| [idx_get](./idx_get/)(int32_t) | Hämtar sida efter index. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Page\>\&) const | Returnerar index för den angivna sidan. |
| [Insert](./insert/)(int32_t) | Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med olika storlekar kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<Page\>\&) | Infogar en sida i sidssamlingen på angiven plats. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) | Infogar sidor från samlingen i dokumentet. |
| [Insert](./insert/)(int32_t, const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) | Infogar sidor från arrayen i dokumentet. |
|  | [Remove](./remove/)(const System::SharedPtr\<Page\>\&) override | Tar bort det angivna objektet, kastar NotSupportedException |
. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
