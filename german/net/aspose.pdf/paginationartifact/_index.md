---
title: Class PaginationArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PaginationArtifact-Klasse. Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar
type: docs
weight: 8260
url: /de/net/aspose.pdf/paginationartifact/
---
## Klasse PaginationArtifact

Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar.

```csharp
public abstract class PaginationArtifact : Artifact
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horizontale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Unterer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Gibt die Sammlung der internen Operatoren des Artefakts zurück. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Gibt den Namen des Artefakt-Subtyps zurück. Kann verwendet werden, wenn der Artefakt-Subtype kein Standard-Subtype ist. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Gibt den Namen des Artefakt-Typs zurück. Kann verwendet werden, wenn der Artefakt-Typ nicht standardmäßig ist. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Gibt die Endseitenzahl für das Artefakt zurück oder setzt sie. Der Wert muss größer oder gleich 0 sein. Wenn ein Wert kleiner als 0 gesetzt wird, wird er auf 0 angepasst. Der Standardwert von 0 bedeutet, dass es keine Endseiten-Grenzen gibt. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Gibt das XForm des Artefakts zurück (wenn XForm verwendet wird). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Gibt das Bild des Artefakts zurück (wenn vorhanden). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Wenn wahr, wird das Artefakt hinter den Seiteninhalten platziert. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Linker Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linien des mehrzeiligen Textartefakts. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Gibt die Opazität des Artefakts zurück oder setzt sie. Mögliche Werte liegen im Bereich 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Gibt die Position des Artefakts zurück oder setzt sie. Wenn diese Eigenschaft angegeben ist, werden Ränder und Ausrichtungen ignoriert. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Gibt das Rechteck des Artefakts zurück. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Rechter Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Gibt den Rotationswinkel des Artefakts zurück oder setzt ihn. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Gibt die Startseitenzahl für das Artefakt zurück oder setzt sie. Der Wert muss größer oder gleich 1 sein. Wenn ein Wert kleiner als 1 gesetzt wird, wird er auf 1 angepasst. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Gibt die Teilmenge von Seiten zurück oder setzt sie, auf die das Artefakt angewendet wird (z. B. alle Seiten, gerade Seiten, ungerade Seiten). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Gibt den Subtyp des Artefakts zurück. Wenn das Artefakt einen nicht standardmäßigen Subtyp hat, kann der Name des Subtyps über CustomSubtype gelesen werden. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Gibt den Text des Artefakts zurück. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textzustand für den Text des Artefakts. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Oberer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Gibt den Typ des Artefakts zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Beginnt verzögerte Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden die Operatoren des Artefakts jedes Mal geändert, wenn eine Eigenschaft des Artefakts geändert wird. Dies führt dazu, dass der Seiteninhalt jedes Mal geändert wird, wenn das Artefakt geändert wird. Um diesen Effekt zu vermeiden, setzen Sie alle Artefakt-Updates zwischen den Aufrufen von StartUpdates/SaveUpdates. Dies ermöglicht es, den Seiteninhalt nur einmal zu ändern. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Gibt das Artefakt frei. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Gibt den benutzerdefinierten Wert des Artefakts zurück. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Entfernt den benutzerdefinierten Wert aus dem Artefakt. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Speichert alle Updates im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Setzt das Bild des Artefakts. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Setzt das Bild des Artefakts. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Setzt den Text und die Texteigenschaften des Artefakts. Ermöglicht die Angabe mehrerer Zeilen. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Setzt, welcher String durch die Seitenzahl ersetzt wird. Der Standardwert ist #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Setzt die PDF-Seite, die als Artefakt auf der Dokumentseite platziert wird. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Setzt den Text des Artefakts. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Setzt den Text und die Texteigenschaften des Artefakts. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Setzt den benutzerdefinierten Wert des Artefakts. |

### Siehe auch

* Klasse [Artifact](../artifact/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)