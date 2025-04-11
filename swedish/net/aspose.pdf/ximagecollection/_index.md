---
title: Class XImageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImageCollection klass. Klass som representerar XImage-samling
type: docs
weight: 11360
url: /sv/net/aspose.pdf/ximagecollection/
---
## XImageCollection klass

Klass som representerar XImage-samling.

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | Antal bilder i samlingen. |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | Returnerar sant om objektet är synkroniserat. |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | Hämtar bild från samlingen efter dess index. (2 indexerare) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | Hämtar array av bildnamn. |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | Returnerar synkroniseringsobjekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | Lägger till enhet i slutet av samlingen, så att enheten kan nås med det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | Lägger till enhet i slutet av samlingen, så att enheten kan nås med det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | Lägger till ny bild i bildlistan. Denna metod lägger till bilden som referens till samma PdfObject (vilket gör att filstorleken kan minskas) |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | Lägger till enhet i slutet av samlingen, så att enheten kan nås med det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | Lägger till enhet i slutet av samlingen, så att enheten kan nås med det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | Lägger till enhet i slutet av samlingen, så att enheten kan nås med det sista indexet. |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | Rensar alla objekt från samlingen. |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | Kopierar array av bilder till samlingen. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | Tar bort bilder från samlingen. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | Tar bort index från samlingen efter index. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | Tar bort objekt från samlingen efter namn. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | Tar bort bild från samlingen efter index och utför åtgärd som anges av åtgärdsparametern. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | Tar bort objekt från samlingen efter namn. |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | Returnerar samlingens uppräkning. |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | Returnerar namnet i bildlistan som är nyckeln till den angivna bilden. |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | Tar bort objekt från samlingen, kastar NotImplementedException. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | Ersätter bild i samlingen med en annan bild. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | Ersätter bild i samlingen med en annan bild. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | Ersätter bild i samlingen med en annan bild. |

### Se Även

* klass [XImage](../ximage/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)