---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontCollection-Klasse. Stellt eine Schriftartensammlung dar
type: docs
weight: 10530
url: /de/net/aspose.pdf.text/fontcollection/
---
## FontCollection-Klasse

Stellt eine Schriftartensammlung dar.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen [`Font`](../font/) Objekte zurück. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Gibt das Schriftartelement am angegebenen Index zurück. (2 Indizes) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die Sammlung zu synchronisieren. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Fügt eine neue Schriftart zu den Schriftressourcen hinzu und gibt den automatisch zugewiesenen Namen der Schriftressource zurück. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Überprüft, ob die Schriftart in der Schriftartensammlung vorhanden ist. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend am angegebenen Index des Zielarrays. |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Löscht das angegebene Element aus der Sammlung. |

## Bemerkungen

Schriftartensammlungen, die durch die `FontCollection`-Klasse dargestellt werden, werden in mehreren Szenarien verwendet. Zum Beispiel in Ressourcen mit der [`Fonts`](../../aspose.pdf/resources/fonts/) Eigenschaft.

## Beispiele

Das Beispiel zeigt, wie man alle auf der Seite deklarierten Schriftarten als eingebettet macht.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Siehe auch

* Klasse [Font](../font/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)