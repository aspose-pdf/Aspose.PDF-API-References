---
title: ListBoxField
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse repräsentiert ListBox-Feld.
type: docs
weight: 3080
url: /de/net/aspose.pdf.forms/listboxfield/
---
## ListBoxField class

Klasse repräsentiert ListBox-Feld.

```csharp
public sealed class ListBoxField : ChoiceField
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ListBoxField](listboxfield#constructor)() | Konstruktor für ListBoxField zur Verwendung im Generator. |
| [ListBoxField](listboxfield#constructor_1)(Document, Rectangle) | Konstruktor für ListBox-Feld. |
| [ListBoxField](listboxfield#constructor_2)(Page, Rectangle) | Erstellt ein neues ListBox-Feld. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Ruft die Anmerkungsaktionen ab. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ruft den aktuellen Darstellungszustand der Anmerkung ab oder legt ihn fest. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Ermittelt oder setzt den alternativen Namen des Feldes (Ein alternativer Feldname , der anstelle des eigentlichen Feldnamens verwendet werden soll, wo immer das Feld in der Benutzeroberfläche identifiziert werden soll). Der alternative Name wird als Feld-Tooltip in Adobe Acrobat verwendet . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Ruft den Index dieser Anmerkung auf der Seite ab oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Ruft die Art der Anmerkung ab. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ruft das Darstellungswörterbuch der Anmerkung ab. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ruft Anmerkungsrandeigenschaften ab oder legt sie fest.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ruft Anmerkungsmerkmale ab. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ruft die Anmerkungsfarbe ab oder legt sie fest. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately) { get; set; } | Holt oder setzt Commit-Flag für Auswahländerung. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ruft den Anmerkungstext ab oder legt ihn fest. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Ruft die Anzahl der Unterfelder in diesem Feld ab oder legt sie fest. (Zum Beispiel Anzahl der Artikel im Optionsfeld). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Ruft die Standarddarstellung des Felds ab oder legt sie fest. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Ruft das exportierbare Flag des Felds ab oder setzt es. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flags der Anmerkung. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ruft den vollständig qualifizierten Namen der Anmerkung ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ruft die Höhe der Anmerkung ab oder legt sie fest. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Anmerkungshervorhebungsmodus. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Holt oder setzt den Fragment-Hyperlink (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist „false“.(für PDF-Generierung) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Erhält oder setzt einen booleschen Wert, der angibt, dass dieses Feld kein Terminalfeld ist, dh eine Gruppe von Feldern. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ruft ab oder legt fest, dass ein Absatz inline ist. Standard ist „false“.(für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Der Standardwert ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite verbleibt. Der Standardwert ist „false“. (für die PDF-Generierung) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Eigenschaft für Generatorunterstützung. Wird verwendet, wenn ein Feld zur Kopf- oder Fußzeile hinzugefügt wird. Wenn wahr, wird dieses Feld einmal erstellt und sein Erscheinungsbild wird auf allen Seiten des Dokuments sichtbar sein. Wenn falsch, wird ein separates Feld für jede Dokumentseite erstellt. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Gibt wahr zurück, wenn das Wörterbuch synchronisiert ist. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Ruft das in diesem Feld enthaltene Unterfeld nach dem Namen des Unterfelds ab. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Ermittelt oder setzt den Mapping-Namen des Felds, das verwendet werden soll, wenn interaktive Formularfelddaten aus dem Dokument exportiert werden. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Liest oder setzt einen Außenrand für Absatz (für PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ruft Datum und Uhrzeit der letzten Änderung der Anmerkung ab oder legt sie fest. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect) { get; set; } | Ruft das Mehrfachauswahl-Flag ab oder setzt es. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ruft den Anmerkungsnamen auf der Seite ab oder legt ihn fest. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Eine Aktion, die ausgeführt werden soll, wenn die Anmerkung aktiviert wird. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options) { get; } | Ruft eine Sammlung von Auswahloptionen ab. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Ruft den Index der Seite ab, die dieses Feld enthält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Ruft die übergeordnete Anmerkung ab. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Ruft den teilweisen Namen des Felds ab oder legt ihn fest. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Ruft den Nur-Lese-Status des Felds ab oder legt ihn fest. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Ruft das Feldrechteck ab oder legt es fest. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Ruft den erforderlichen Status des Felds ab oder legt ihn fest. |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected) { set; } | Ruft den Index des ausgewählten Elements ab oder legt ihn fest. Artikel sind ab 1. nummeriert |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems) { set; } | Ruft ein Array der ausgewählten Elemente in der Mehrfachauswahlliste ab oder legt es fest. Für eine Einzelauswahlliste wird ein Array mit einem einzelnen Element zurückgegeben. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ruft das Darstellungswörterbuch der Anmerkung ab. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Synchronisationsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Ruft die Tab-Reihenfolge des Felds ab oder legt sie fest. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ruft die Textausrichtung für Anmerkungen ab oder legt sie fest. |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex) { get; set; } | Ruft den Index des obersten sichtbaren Elements der Liste ab oder setzt ihn. |
| override [Value](../../aspose.pdf.forms/choicefield/value) { get; set; } | Ruft den Wert des Felds ab oder legt ihn fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Holt oder setzt eine vertikale Ausrichtung des Absatzes |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ruft die Breite der Anmerkung ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Diagramms angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Grafik mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Akzeptiert Besucher. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string) | Fügt eine neue Option mit dem angegebenen Namen hinzu. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string, string) | Fügt eine neue Option mit dem angegebenen Exportwert und Namen hinzu. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Aktualisieren Sie Parameter und Aussehen gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klont diese Instanz. Virtuelle Methode. Immer null zurückgeben. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Kopiert Unterfelder dieses Felds in ein Array, beginnend mit dem angegebenen Index. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption)(string) | Löscht die Option nach ihrem Namen. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Entfernt dieses Feld und platziert seinen Wert direkt auf der Seite. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Gibt den Enumerator der enthaltenen Felder zurück. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitendrehung berücksichtigt wird. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Berechnet alle berechneten Felder im Formular neu. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Position des Feldes setzen. |

### Siehe auch

* class [ChoiceField](../choicefield)
* namensraum [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
