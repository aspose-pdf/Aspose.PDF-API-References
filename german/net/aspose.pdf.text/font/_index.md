---
title: Font
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt das Schriftobjekt dar.
type: docs
weight: 6690
url: /de/net/aspose.pdf.text/font/
---
## Font class

Stellt das Schriftobjekt dar.

```csharp
public sealed class Font
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont) { get; } | Ruft den BaseFont-Wert des PDF-Schriftartenobjekts ab. Auch bekannt als PostScript-Name der Schriftart. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname) { get; } | Manchmal können PDF-Schriftarten (normalerweise chinesische/japanische/koreanische Schriftarten) einen bestimmten Schriftartnamen haben. Dieser Name ist der Wert der PDF-Schriftarteneigenschaft "BaseFont", und manchmal könnte diese Eigenschaft in hexadezimaler Form dargestellt werden. Wenn dieser Name direkt gelesen wird, könnte er in nicht lesbarer Form dargestellt werden. Um eine lesbare Form zu erhalten, ist es notwendig, den Namen der Schriftart nach Regeln zu entschlüsseln, die für diese Schriftart spezifisch sind. Diese Eigenschaft gibt den decodierten Schriftartnamen zurück, also verwenden Sie sie für Fälle, in denen Sie mit einem nicht lesbaren treffen[`FontName`](./fontname) . Wenn Eigenschaft[`FontName`](./fontname) hat eine lesbare Form, diese Eigenschaft ist die gleiche wie [`FontName`](./fontname) , sodass Sie diese Eigenschaft für alle Fälle verwenden können, in denen Sie den Schriftartnamen in lesbarer Form erhalten müssen. |
| [FontName](../../aspose.pdf.text/font/fontname) { get; } | Ruft den Namen der Schriftart ab[`Font`](../font) Objekt. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions) { get; } | Nützliche Eigenschaften zum Optimieren des Schriftverhaltens |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible) { get; } | Ruft ab, ob die Schriftart im System vorhanden (installiert) ist. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart eingebettet ist. |
| [IsSubset](../../aspose.pdf.text/font/issubset) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart eine Teilmenge ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror)() | Ein Ziel dieser Methode - Fehlerbeschreibung zurückzugeben, wenn ein Versuch zum Einbetten einer Schriftart fehlgeschlagen ist. Wenn es keine Fehlerfälle gibt, wird eine leere Zeichenfolge zurückgegeben. |
| [MeasureString](../../aspose.pdf.text/font/measurestring)(string, float) | Misst die Zeichenfolge. |
| [Save](../../aspose.pdf.text/font/save)(Stream) | Speichert die Schriftart im Stream. Beachten Sie, dass die Schriftart im TTF-Zwischenformat gespeichert wird, das nur für die Verwendung in einer konvertierten Kopie des Originaldokuments vorgesehen ist. Die Schriftartdatei ist nicht für die Verwendung außerhalb des Kontexts des Originaldokuments vorgesehen. |

### Beispiele

Das Beispiel zeigt, wie Text auf der ersten Seite gesucht und die Schriftart eines ersten Suchvorkommens geändert wird.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Schriftart erstellen und zum Einbetten markieren
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Schriftart des ersten Textvorkommens ändern
absorber.TextFragments[1].TextState.Font = font;


// Dokument speichern
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [FontRepository](../fontrepository)
* class [Document](../../aspose.pdf/document)
* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->