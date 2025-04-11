---
title: Class BatesNArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BatesNArtifact-Klasse. Klasse beschreibt Bates-Nummerierungsartefakt
type: docs
weight: 2850
url: /de/net/aspose.pdf/batesnartifact/
---
## BatesNArtifact-Klasse

Klasse beschreibt Bates-Nummerierungsartefakt.

```csharp
public class BatesNArtifact : PaginationArtifact
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BatesNArtifact](batesnartifact/)() | Initialisiert eine neue Instanz der `BatesNArtifact`-Klasse. Dieser Konstruktor ist intern und erstellt eine Header-Artefaktinstanz mit Standardwerten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horizontale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Unterer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Gibt die Sammlung der internen Operatoren des Artefakts zurück. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Gibt den Namen des Artefakt-Subtyps zurück. Kann verwendet werden, wenn der Artefakt-Subtype kein Standard-Subtype ist. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Gibt den Namen des Artefakt-Typs zurück. Kann verwendet werden, wenn der Artefakt-Typ nicht standardmäßig ist. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Gibt die Endseitenzahl für das Artefakt zurück oder setzt sie. Der Wert muss größer oder gleich 0 sein. Wenn ein Wert kleiner als 0 gesetzt wird, wird er auf 0 angepasst. Der Standardwert von 0 bedeutet, dass es keine Endseiten-Grenzen gibt. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Gibt das XForm des Artefakts zurück (falls XForm verwendet wird). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Gibt das Bild des Artefakts zurück (falls vorhanden). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Wenn wahr, wird das Artefakt hinter den Seiteninhalten platziert. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Linker Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linien des mehrzeiligen Textartefakts. |
| [NumberOfDigits](../../aspose.pdf/batesnartifact/numberofdigits/) { get; set; } | Gibt die Anzahl der Ziffern für die Bates-Nummerierung zurück oder setzt sie. Der Wert muss zwischen 3 und 15 (einschließlich) liegen. Wenn ein Wert kleiner als 3 gesetzt wird, wird er auf 3 angepasst. Wenn ein Wert größer als 15 gesetzt wird, wird er auf 15 angepasst. Der Standardwert ist 6. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Gibt die Opazität des Artefakts zurück oder setzt sie. Mögliche Werte liegen im Bereich 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Gibt die Position des Artefakts zurück oder setzt sie. Wenn diese Eigenschaft angegeben ist, werden Ränder und Ausrichtungen ignoriert. |
| [Prefix](../../aspose.pdf/batesnartifact/prefix/) { get; set; } | Gibt das Präfix zurück oder setzt es, das zur Bates-Nummer hinzugefügt werden soll. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Gibt das Rechteck des Artefakts zurück. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Rechter Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Gibt den Rotationswinkel des Artefakts zurück oder setzt ihn. |
| [StartNumber](../../aspose.pdf/batesnartifact/startnumber/) { get; set; } | Gibt die Startnummer für die Bates-Nummerierung zurück oder setzt sie. Der Wert muss größer oder gleich 1 sein. Wenn ein Wert kleiner als 1 gesetzt wird, wird er auf 1 angepasst. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Gibt die Startseitenzahl für das Artefakt zurück oder setzt sie. Der Wert muss größer oder gleich 1 sein. Wenn ein Wert kleiner als 1 gesetzt wird, wird er auf 1 angepasst. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Gibt die Teilmenge der Seiten zurück oder setzt sie, auf die das Artefakt angewendet wird (z. B. alle Seiten, gerade Seiten, ungerade Seiten). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Gibt den Artefakt-Subtype zurück. Wenn das Artefakt einen nicht standardmäßigen Subtyp hat, kann der Name des Subtyps über CustomSubtype gelesen werden. |
| [Suffix](../../aspose.pdf/batesnartifact/suffix/) { get; set; } | Gibt das Suffix zurück oder setzt es, das zur Bates-Nummer hinzugefügt werden soll. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Gibt den Text des Artefakts zurück oder setzt ihn. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textzustand für den Artefakttext. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Oberer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Gibt den Artefakt-Typ zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Beginnt verzögerte Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden die Artefakt-Operatoren jedes Mal geändert, wenn eine Artefakteigenschaft geändert wird. Dies führt dazu, dass der Seiteninhalt jedes Mal geändert wird, wenn das Artefakt geändert wird. Um diesen Effekt zu vermeiden, setzen Sie alle Artefakt-Updates zwischen den Aufrufen von StartUpdates/SpeichernUpdates. Dies ermöglicht es, den Seiteninhalt nur einmal zu ändern. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Gibt das Artefakt frei. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Gibt den benutzerdefinierten Wert des Artefakts zurück. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Entfernt den benutzerdefinierten Wert aus dem Artefakt. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Speichert alle Updates im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Setzt das Bild des Artefakts. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Setzt das Bild des Artefakts. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Setzt Text und Texteigenschaften des Artefakts. Ermöglicht die Angabe mehrerer Zeilen. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Setzt, welcher String durch die Seitenzahl ersetzt wird. Der Standardwert ist #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Setzt die PDF-Seite, die als Artefakt auf der Dokumentseite platziert wird. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Setzt den Text des Artefakts. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Setzt Text und Texteigenschaften des Artefakts. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Setzt den benutzerdefinierten Wert des Artefakts. |

### Siehe auch

* Klasse [PaginationArtifact](../paginationartifact/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)