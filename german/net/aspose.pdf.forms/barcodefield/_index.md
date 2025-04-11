---
title: Class BarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.BarcodeField-Klasse. Klasse stellt Barcode-Feld dar
type: docs
weight: 4950
url: /de/net/aspose.pdf.forms/barcodefield/
---
## BarcodeField-Klasse

Klasse stellt Barcode-Feld dar.

```csharp
public sealed class BarcodeField : TextBoxField
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BarcodeField](barcodefield/#constructor)(Dokument, Rechteck) | Initialisiert eine neue Instanz der `BarcodeField`-Klasse. |
| [BarcodeField](barcodefield/#constructor_1)(Seite, Rechteck) | Initialisiert eine neue Instanz der `BarcodeField`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Gibt die Aktionsannotation zurück. (2 Eigenschaften) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gibt den aktuellen Erscheinungszustand der Annotation zurück oder setzt ihn. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Gibt den alternativen Namen des Feldes zurück oder setzt ihn (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens verwendet werden soll, wo immer das Feld in der Benutzeroberfläche identifiziert werden soll). Der alternative Name wird als Feldtooltip in Adobe Acrobat verwendet. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Gibt den Index dieser Annotation auf der Seite zurück oder setzt ihn. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Gibt den Typ der Annotation zurück. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gibt das Erscheinungswörterbuch der Annotation zurück. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gibt die Eigenschaften des Randes der Annotation zurück oder setzt sie. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Caption](../../aspose.pdf.forms/barcodefield/caption/) { get; } | Gibt die Beschriftung des Barcode-Objekts zurück. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gibt die Eigenschaften der Annotation zurück. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gibt die Farbe der Annotation zurück oder setzt sie. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gibt den Text der Annotation zurück oder setzt ihn. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Gibt die Anzahl der Unterfelder in diesem Feld zurück. (Zum Beispiel die Anzahl der Elemente im Optionsfeld). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Gibt das Standard-Erscheinungsbild des Feldes zurück oder setzt es. |
| [ECC](../../aspose.pdf.forms/barcodefield/ecc/) { get; } | Gibt einen ganzzahligen Wert zurück, der den Fehlerkorrekturkoeffizienten darstellt. Für PDF417 sollte er von 0 bis 8 reichen. Für QRCode sollte er von 0 bis 3 reichen (0 für 'L', 1 für 'M', 2 für 'Q' und 3 für 'H'). |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Gibt das exportierbare Flag des Feldes zurück oder setzt es. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Gibt das Flag zurück oder setzt es, das angibt, ob das Feld in getrennte Positionen unterteilt ist. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gibt den vollqualifizierten Namen der Annotation zurück. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gibt die Höhe der Annotation zurück oder setzt sie. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Hervorhebungsmodus der Annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gibt den Fragment-Hyperlink zurück oder setzt ihn (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für PDF-Generierung) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob dieses Feld ein nicht-terminales Feld ist, d.h. eine Gruppe von Feldern. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder setzt, ob ein Absatz inline ist. Standard ist falsch. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für PDF-Generierung) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Eigenschaft für Generatorunterstützung. Wird verwendet, wenn das Feld in den Kopf- oder Fußbereich eingefügt wird. Wenn wahr, wird dieses Feld einmal erstellt und sein Erscheinungsbild wird auf allen Seiten des Dokuments sichtbar sein. Wenn falsch, wird für jede Dokumentseite ein separates Feld erstellt. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Gibt wahr zurück, wenn das Wörterbuch synchronisiert ist. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Gibt das Unterfeld zurück, das in diesem Feld nach dem Namen des Unterfeldes enthalten ist. (2 Indizes) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Gibt den Mapping-Namen des Feldes zurück oder setzt ihn, der beim Exportieren von interaktiven Formulardaten aus dem Dokument verwendet werden soll. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt einen äußeren Rand für den Absatz zurück oder setzt ihn (für PDF-Generierung) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Gibt die maximale Länge des Textes im Feld zurück oder setzt sie. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder setzt sie, wann die Annotation zuletzt geändert wurde. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Gibt das Multiline-Flag des Feldes zurück oder setzt es. Wenn Multiline wahr ist, kann das Feld mehrere Zeilen Text enthalten. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gibt den Namen der Annotation auf der Seite zurück oder setzt ihn. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Gibt den Index der Seite zurück, die dieses Feld enthält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Gibt die übergeordnete Annotation zurück. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Gibt den teilweisen Namen des Feldes zurück oder setzt ihn. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Gibt den schreibgeschützten Status des Feldes zurück oder setzt ihn. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Gibt das Rechteck des Feldes zurück oder setzt es. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Gibt den erforderlichen Status des Feldes zurück oder setzt ihn. |
| [Resolution](../../aspose.pdf.forms/barcodefield/resolution/) { get; } | Gibt die Auflösung in Punkten pro Zoll (dpi) zurück, bei der das Barcode-Objekt gerendert wird. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Gibt das scrollbare Flag des Feldes zurück oder setzt es. Wenn wahr, kann das Feld gescrollt werden. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Gibt das Rechtschreibprüfungs-Flag für das Feld zurück oder setzt es. Wenn wahr, wird das Feld auf Rechtschreibung überprüft. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gibt das Erscheinungswörterbuch der Annotation zurück. |
| [Symbology](../../aspose.pdf.forms/barcodefield/symbology/) { get; } | Gibt an, welche Barcode- oder Glyphentechnologie für diese Annotation verwendet werden soll, siehe [`Symbology`](./symbology/) für Details. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronisationsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Gibt die Tabulatorreihenfolge des Feldes zurück oder setzt sie. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gibt die Textausrichtung für die Annotation zurück oder setzt sie. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | Gibt die vertikale Textausrichtung für die Annotation zurück oder setzt sie. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Gibt den Wert des Feldes zurück oder setzt ihn. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gibt eine vertikale Ausrichtung des Absatzes zurück oder setzt sie. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gibt die Breite der Annotation zurück oder setzt sie. |
| [XSymHeight](../../aspose.pdf.forms/barcodefield/xsymheight/) { get; } | Gibt den vertikalen Abstand zwischen zwei Barcode-Modulen in Pixeln zurück. Das Verhältnis XSymHeight/XSymWidth sollte ein ganzzahliger Wert sein. Für PDF417 liegt der akzeptable Verhältnisbereich zwischen 1 und 4. Für QRCode und DataMatrix sollte dieses Verhältnis immer 1 sein. |
| [XSymWidth](../../aspose.pdf.forms/barcodefield/xsymwidth/) { get; } | Gibt den horizontalen Abstand in Pixeln zwischen zwei Barcode-Modulen zurück. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder setzt ihn, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Akzeptiert den Besucher. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | Fügt den Barcode 128 in das Feld ein. Der Feldwert wird auf den Code geändert und das Feld wird schreibgeschützt. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | Fügt ein Bild in die Ressourcen des Feldes ein und zeichnet es. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Führt eine bestimmte JavaScript-Aktion für das Feld aus. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in die angegebene Datei. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exportiert den Inhalt des angegebenen Feldes in einen JSON-Stream. Der Wert des Schaltflächenfeldes wird nicht exportiert. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Entfernt dieses Feld und platziert seinen Wert direkt auf der Seite. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Gibt den Namen des "ausgewählten" Zustands gemäß den vorhandenen Zustandsnamen zurück. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Gibt den Enumerator der enthaltenen Felder zurück. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importiert Daten in die angegebenen Felder aus einem JSON-Stream, basierend auf einer genauen Übereinstimmung der vollständigen Namen der Felder. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importiert Daten in das angegebene Feld aus einem JSON-Stream, wobei der vollständige Name, der in der Variablen 'fieldFullNameInJSON' angegeben ist, für die Übereinstimmung verwendet wird. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Berechnet alle berechneten Felder im Formular neu. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Setzt die Position des Feldes. |

### Siehe auch

* Klasse [TextBoxField](../textboxfield/)
* Namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../)