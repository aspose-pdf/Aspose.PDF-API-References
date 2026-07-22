---
title: "Aspose::Pdf::XImageCollection klass"
linktitle: "XImageCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XImageCollection klass. Klass som representerar XImage-samlingen i C++."
type: docs
weight: 19900
url: /sv/cpp/aspose.pdf/ximagecollection/
---
## XImageCollection class


Klass som representerar [XImage](../ximage/) samlingen.

```cpp
class XImageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Aspose::Pdf::XImage>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](./add/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::ImageFilterType) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](./add/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&, Aspose::Pdf::ImageFilterType) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [AddWithName](./addwithname/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Lägger till en ny bild i [Image](../image/)-listan. Denna metod lägger till bilden som referens till samma PdfObject (vilket möjliggör minskning av filstorleken) |
| [Clear](./clear/)() override | Rensar alla objekt från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) const override | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Aspose::Pdf::XImage\>\>, int32_t) override | Kopierar en array av bilder till samlingen. |
| [Delete](./delete/)(int32_t) | Tar bort index från samlingen efter index. |
| [Delete](./delete/)(int32_t, Aspose::Pdf::ImageDeleteAction) | Tar bort bild från samlingen enligt index och utför den åtgärd som anges av åtgärdsparametern. |
| [Delete](./delete/)(const System::String\&) | Tar bort objekt från samlingen efter namn. |
| [Delete](./delete/)(const System::String\&, Aspose::Pdf::ImageDeleteAction) | Tar bort objekt från samlingen efter namn. |
| [Delete](./delete/)() | Raderar bilder från samlingen. |
| [get_Count](./get_count/)() const override | Antal bilder i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om objektet är synkroniserat. |
| [get_Names](./get_names/)() | Hämtar en array med bildnamn. |
| [get_SyncRoot](./get_syncroot/)() const | Returnerar synkroniseringsobjekt. |
| [GetEnumerator](./getenumerator/)() override | Returnerar samlingens enumerator. |
| [GetImageName](./getimagename/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Returnerar namn i bildlistan som är nyckeln för den angivna bilden. |
| [idx_get](./idx_get/)(int32_t) | Hämtar bild från samlingen enligt dess index. |
| [idx_get](./idx_get/)(const System::String\&) | Hämtar bild från samlingen enligt dess namn. |
|  | [Remove](./remove/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) override | Tar bort ett objekt från samlingen, kastar NotImplementedException |
. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&) | Ersätt bild i samlingen med en annan bild. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, bool) | Ersätt bild i samlingen med en annan bild. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Ersätt bild i samlingen med en annan bild. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
