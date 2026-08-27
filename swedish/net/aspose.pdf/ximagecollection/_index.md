---
title: "Klass XImageCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.XImageCollection‑klass. Klass som representerar XImage‑samling"
type: docs
weight: 11550
url: /sv/net/aspose.pdf/ximagecollection/
---
## XImageCollection class

Klassen representerar XImage‑samling.

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | Antal bilder i samlingen. |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | Returnerar true om objektet är synkroniserat. |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | Hämtar bild från samlingen med dess index. (2 indexerare) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | Hämtar en array med bildnamn. |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | Returnerar synkroniseringsobjektet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | Lägger till en ny bild i bildlistan. Denna metod lägger till bilden som referens till samma PdfObject (vilket möjliggör minskad filstorlek) |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | Rensar alla objekt från samlingen. |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | Kopierar en array med bilder till samlingen. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | Tar bort bilder från samlingen. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | Tar bort ett index från samlingen med angivet index. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | Tar bort ett objekt från samlingen efter namn. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | Tar bort bild från samlingen med index och utför den åtgärd som anges av parametern action. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | Tar bort ett objekt från samlingen efter namn. |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | Returnerar en enumerator för samlingen. |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | Returnerar namn i bildlistan som är nyckeln för den angivna bilden. |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | Tar bort objekt från samlingen, kastar NotImplementedException. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | Ersätt bilden i samlingen med en annan bild. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | Ersätt bilden i samlingen med en annan bild. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | Ersätt bilden i samlingen med en annan bild. |

### Se även

* class [XImage](../ximage/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


