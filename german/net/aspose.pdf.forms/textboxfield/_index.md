---
title: Class TextBoxField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.TextBoxField-Klasse. Klasse, die ein Textfeld darstellt
type: docs
weight: 5320
url: /de/net/aspose.pdf.forms/textboxfield/
---
## TextBoxField-Klasse

Klasse, die ein Textfeld darstellt.

```csharp
public class TextBoxField : Field
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextBoxField](textboxfield/#constructor_1)(Document) | Konstruktor, der mit Generator verwendet werden sollte. |
| [TextBoxField](textboxfield/#constructor_2)(Document, Rectangle) | Konstruktor des TextBox-Feldes. |
| [TextBoxField](textboxfield/#constructor_3)(Page, Rectangle) | Konstruktor des TextBox-Feldes. |
| [TextBoxField](textboxfield/#constructor_4)(Page, Rectangle[]) | Konstruktor des TextBox-Feldes. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Ruft die Aktionsannotation ab. (2 Eigenschaften) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ruft den aktuellen Erscheinungszustand der Annotation ab oder setzt ihn. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Ruft den alternativen Namen des Feldes ab oder setzt ihn (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens verwendet werden soll, wo immer das Feld in der Benutzeroberfläche identifiziert werden soll). Der alternative Name wird als Tooltip für das Feld in Adobe Acrobat verwendet. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Ruft den Index dieser Annotation auf der Seite ab oder setzt ihn. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Ruft den Typ der Annotation ab. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ruft die Eigenschaften des Randes der Annotation ab oder setzt sie. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ruft die Eigenschaften der Annotation ab. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ruft die Farbe der Annotation ab oder setzt sie. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ruft den Text der Annotation ab oder setzt ihn. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Ruft die Anzahl der Unterfelder in diesem Feld ab. (Zum Beispiel die Anzahl der Elemente im Optionsfeld). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Ruft das Standard-Erscheinungsbild des Feldes ab oder setzt es. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Ruft das exportierbare Flag des Feldes ab oder setzt es. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Ruft das Flag ab oder setzt es, das angibt, ob das Feld in gleichmäßige Positionen unterteilt ist. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ruft den vollqualifizierten Namen der Annotation ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ruft die Höhe der Annotation ab oder setzt sie. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Hervorhebungsmodus der Annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink ab oder setzt ihn (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für PDF-Generierung) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob dieses Feld ein nicht-terminales Feld ist, d.h. eine Gruppe von Feldern. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft einen Absatz ab oder setzt ihn, der inline ist. Standard ist false. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für PDF-Generierung) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Eigenschaft für Generatorunterstützung. Wird verwendet, wenn das Feld in den Kopf- oder Fußbereich eingefügt wird. Wenn true, wird dieses Feld einmal erstellt und sein Erscheinungsbild wird auf allen Seiten des Dokuments sichtbar sein. Wenn false, wird für jede Dokumentseite ein separates Feld erstellt. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Gibt true zurück, wenn das Wörterbuch synchronisiert ist. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Ruft das Unterfeld ab, das in diesem Feld nach dem Namen des Unterfeldes enthalten ist. (2 Indizes) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Ruft den Mapping-Namen des Feldes ab oder setzt ihn, der beim Exportieren von interaktiven Formulardaten aus dem Dokument verwendet werden soll. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder setzt ihn (für PDF-Generierung) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Ruft die maximale Länge des Textes im Feld ab oder setzt sie. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ruft das Datum und die Uhrzeit ab oder setzt sie, wann die Annotation zuletzt geändert wurde. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Ruft das Multiline-Flag des Feldes ab oder setzt es. Wenn Multiline true ist, kann das Feld mehrere Textzeilen enthalten. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ruft den Namen der Annotation auf der Seite ab oder setzt ihn. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Ruft den Index der Seite ab, die dieses Feld enthält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Ruft die übergeordnete Annotation ab. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Ruft den teilweisen Namen des Feldes ab oder setzt ihn. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Ruft den schreibgeschützten Status des Feldes ab oder setzt ihn. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Ruft das Rechteck des Feldes ab oder setzt es. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Ruft den erforderlichen Status des Feldes ab oder setzt ihn. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Ruft das scrollbare Flag des Feldes ab oder setzt es. Wenn true, kann das Feld gescrollt werden. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Ruft das Rechtschreibprüfungs-Flag für das Feld ab oder setzt es. Wenn true, wird das Feld auf Rechtschreibung überprüft. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronisationsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Ruft die Tabulatorreihenfolge des Feldes ab oder setzt sie. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ruft die Textausrichtung für die Annotation ab oder setzt sie. |
| [TextVerticalAlignment](../../aspose.pdf/forms/textboxfield/textverticalalignment/) { get; set; } | Ruft die vertikale Textausrichtung für die Annotation ab oder setzt sie. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Ruft den Wert des Feldes ab oder setzt ihn. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft eine vertikale Ausrichtung des Absatzes ab oder setzt sie. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ruft die Breite der Annotation ab oder setzt sie. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder setzt ihn, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Akzeptiert Besucher. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | Fügt einen Barcode 128 in das Feld ein. Der Feldwert wird auf den Code geändert und das Feld wird schreibgeschützt. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | Fügt ein Bild in die Ressourcen des Feldes ein und zeichnet es. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Führt eine bestimmte JavaScript-Aktion für das Feld aus. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in die angegebene Datei. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exportiert den Inhalt des angegebenen Feldes in einen JSON-Stream. Der Wert des Schaltflächenfeldes wird nicht exportiert. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Entfernt dieses Feld und platziert seinen Wert direkt auf der Seite. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Gibt den Namen des "überprüften" Zustands gemäß den vorhandenen Zustandsnamen zurück. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Gibt den Enumerator der enthaltenen Felder zurück. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importiert Daten in die angegebenen Felder aus einem JSON-Stream, basierend auf einer genauen Übereinstimmung der vollständigen Namen der Felder. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importiert Daten in das angegebene Feld aus einem JSON-Stream, wobei der vollständige Name, der in der Variablen 'fieldFullNameInJSON' angegeben ist, für die Übereinstimmung verwendet wird. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Berechnet alle berechneten Felder im Formular neu. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Setzt die Position des Feldes. |

### Siehe auch

* Klasse [Field](../field/)
* Namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../)