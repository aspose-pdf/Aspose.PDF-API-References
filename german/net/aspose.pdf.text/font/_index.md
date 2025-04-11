---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.Font-Klasse. Stellt Schriftartobjekt dar
type: docs
weight: 10510
url: /de/net/aspose.pdf.text/font/
---
## Schriftartklasse

Stellt Schriftartobjekt dar.

```csharp
public sealed class Font
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Gibt den BaseFont-Wert des PDF-Schriftartobjekts zurück. Auch bekannt als PostScript-Name der Schriftart. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Manchmal können PDF-Schriftarten (normalerweise chinesische/japanische/koreanische Schriftarten) einen spezifischen Schriftartnamen haben. Dieser Name ist der Wert der PDF-Schriftarteigenschaft "BaseFont" und manchmal kann diese Eigenschaft in hexadezimaler Form dargestellt werden. Wenn man diesen Namen direkt liest, kann er in nicht lesbarer Form dargestellt werden. Um eine lesbare Form zu erhalten, ist es notwendig, den Namen der Schriftart nach Regeln zu dekodieren, die spezifisch für diese Schriftart sind. Diese Eigenschaft gibt den dekodierten Schriftartnamen zurück, verwenden Sie ihn also für Fälle, in denen Sie auf einen nicht lesbaren [`FontName`](./fontname/) stoßen. Wenn die Eigenschaft [`FontName`](./fontname/) eine lesbare Form hat, wird diese Eigenschaft die gleiche wie [`FontName`](./fontname/) sein, sodass Sie diese Eigenschaft in allen Fällen verwenden können, in denen Sie den Schriftartnamen in lesbarer Form benötigen. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Gibt den Schriftartnamen des `Font`-Objekts zurück. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Nützliche Eigenschaften zur Anpassung des Verhaltens der Schriftart |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Gibt an, ob die Schriftart im System vorhanden (installiert) ist. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Gibt einen Wert zurück oder legt einen Wert fest, der angibt, ob die Schriftart eingebettet ist. Schriftarten, die auf IFont basieren, werden automatisch unterteilt und eingebettet. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Gibt einen Wert zurück oder legt einen Wert fest, der angibt, ob die Schriftart ein Subset ist. Schriftarten, die auf IFont basieren, werden automatisch unterteilt und eingebettet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Ziel dieser Methode ist es, eine Beschreibung des Fehlers zurückzugeben, wenn der Versuch, die Schriftart einzubetten, fehlgeschlagen ist. Wenn es keine Fehlerfälle gibt, wird ein leerer String zurückgegeben. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Misst den String. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Speichert die Schriftart im Stream. Beachten Sie, dass die Schriftart im Zwischenformat TTF gespeichert wird, das nur für eine konvertierte Kopie des ursprünglichen Dokuments verwendet werden soll. Die Schriftartdatei ist nicht dafür gedacht, außerhalb des Kontexts des ursprünglichen Dokuments verwendet zu werden. |

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und die Schriftart des ersten Suchvorkommens ändert.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../textfragmentabsorber/)
* Klasse [FontRepository](../fontrepository/)
* Klasse [Document](../../aspose.pdf/document/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)