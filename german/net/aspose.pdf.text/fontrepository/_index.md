---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontRepository-Klasse. Führt eine Schriftartsuche durch. Sucht in systeminstallierten Schriftarten und Standard-PDF-Schriftarten. Bietet auch die Funktionalität zum Öffnen benutzerdefinierter Schriftarten.
type: docs
weight: 10540
url: /de/net/aspose.pdf.text/fontrepository/
---
## FontRepository-Klasse

Führt eine Schriftartsuche durch. Sucht in systeminstallierten Schriftarten und Standard-PDF-Schriftarten. Bietet auch die Funktionalität zum Öffnen benutzerdefinierter Schriftarten.

```csharp
public sealed class FontRepository
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FontRepository](fontrepository/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Gibt die Sammlung der Schriftartquellen zurück. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Gibt die Sammlung der Schriftartsubstitutionsstrategien zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück, wobei die Groß- und Kleinschreibung ignoriert oder beachtet wird. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück, wobei die Groß- und Kleinschreibung ignoriert oder beachtet wird. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Lädt systeminstallierte Schriftarten und Standard-PDF-Schriftarten. Diese Methode wurde entwickelt, um den Schriftartenladeprozess zu beschleunigen. Standardmäßig werden Schriftarten bei der ersten Anfrage für eine beliebige Schriftart geladen. Die Verwendung dieser Methode lädt system- und standardmäßige PDF-Schriftarten sofort, bevor ein PDF-Dokument geöffnet wird. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Öffnet die Schriftart mit dem angegebenen Schriftartdateipfad. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Öffnet die Schriftart mit dem angegebenen Schriftstrom. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Öffnet die Schriftart mit dem angegebenen Schriftartdateipfad und dem Metrikdateipfad. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Lädt alle Schriftarten neu, die durch die Eigenschaft [`Sources`](./sources/) angegeben sind. |

## Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../textfragmentabsorber/)
* Klasse [Document](../../aspose.pdf/document/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)