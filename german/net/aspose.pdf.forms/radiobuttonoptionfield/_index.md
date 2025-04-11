---
title: Class RadioButtonOptionField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.RadioButtonOptionField-Klasse. Klasse repräsentiert ein Element des RadioButton-Feldes
type: docs
weight: 5220
url: /de/net/aspose.pdf.forms/radiobuttonoptionfield/
---
## RadioButtonOptionField-Klasse

Klasse repräsentiert ein Element des RadioButton-Feldes.

```csharp
public sealed class RadioButtonOptionField : Field
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RadioButtonOptionField](radiobuttonoptionfield/#constructor)() | Erstellt eine neue Instanz von RadioButtonOptionField. |
| [RadioButtonOptionField](radiobuttonoptionfield/#constructor_1)(Seite, Rechteck) | Erstellt einen RadioButton im angegebenen Rechteck auf der angegebenen Seite. |

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
| [Caption](../../aspose.pdf.forms/radiobuttonoptionfield/caption/) { get; set; } | Ruft die Beschriftung ab oder setzt sie. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ruft die Eigenschaften der Annotation ab. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ruft die Farbe der Annotation ab oder setzt sie. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ruft den Text der Annotation ab oder setzt ihn. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Ruft die Anzahl der Unterfelder in diesem Feld ab. (Zum Beispiel die Anzahl der Elemente im RadioButton-Feld). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Ruft das Standard-Erscheinungsbild des Feldes ab oder setzt es. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Ruft das exportierbare Flag des Feldes ab oder setzt es. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ruft den vollqualifizierten Namen der Annotation ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ruft die Höhe der Annotation ab oder setzt sie. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Hervorhebungsmodus der Annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für den PDF-Generator) ab oder setzt ihn. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für die PDF-Generierung) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob dieses Feld ein nicht-terminales Feld ist, d.h. eine Gruppe von Feldern. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft einen Absatz ab oder setzt ihn, der inline ist. Standard ist falsch. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für die PDF-Generierung) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Eigenschaft für die Generatorunterstützung. Wird verwendet, wenn das Feld in den Kopf- oder Fußbereich eingefügt wird. Wenn wahr, wird dieses Feld einmal erstellt und sein Erscheinungsbild wird auf allen Seiten des Dokuments sichtbar sein. Wenn falsch, wird für jede Dokumentseite ein separates Feld erstellt. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Gibt true zurück, wenn das Wörterbuch synchronisiert ist. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Ruft das Unterfeld ab, das in diesem Feld nach dem Namen des Unterfeldes enthalten ist. (2 Indizes) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Ruft den Mapping-Namen des Feldes ab oder setzt ihn, der beim Exportieren von interaktiven Formulardaten aus dem Dokument verwendet werden soll. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder setzt ihn (für die PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ruft das Datum und die Uhrzeit ab oder setzt sie, wann die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ruft den Namen der Annotation auf der Seite ab oder setzt ihn. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird. |
| [OptionName](../../aspose.pdf.forms/radiobuttonoptionfield/optionname/) { get; set; } | Ruft den Namen der Option ab oder setzt ihn. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Ruft den Index der Seite ab, die dieses Feld enthält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Ruft den übergeordneten Annotation ab. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Ruft den teilweisen Namen des Feldes ab oder setzt ihn. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Ruft den schreibgeschützten Status des Feldes ab oder setzt ihn. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Ruft das Rechteck des Feldes ab oder setzt es. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Ruft den erforderlichen Status des Feldes ab oder setzt ihn. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [Style](../../aspose.pdf.forms/radiobuttonoptionfield/style/) { get; set; } | Ruft den Stil des Kontrollkästchens ab oder setzt ihn. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronisationsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Ruft die Tabulatorreihenfolge des Feldes ab oder setzt sie. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ruft die Textausrichtung für die Annotation ab oder setzt sie. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | Ruft den Wert des Feldes ab oder setzt ihn. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft eine vertikale Ausrichtung des Absatzes ab oder setzt sie. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ruft die Breite der Annotation ab oder setzt sie. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder setzt ihn, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Akzeptiert den Besucher. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Führt eine angegebene JavaScript-Aktion für das Feld aus. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in die angegebene Datei. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exportiert den Inhalt des angegebenen Feldes in einen JSON-Stream. Werte von Schaltflächenfeldern werden nicht exportiert. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Entfernt dieses Feld und platziert seinen Wert direkt auf der Seite. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Gibt den Namen des "ausgewählten" Zustands gemäß den vorhandenen Zustandsnamen zurück. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Gibt den Enumerator der enthaltenen Felder zurück. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importiert Daten in die angegebenen Felder aus einem JSON-Stream, basierend auf einer genauen Übereinstimmung der vollständigen Namen der Felder. |
| [ImportValueFromJson](../../aspose.pdf/forms/field/importvaluefromjson/)(Stream, string) | Importiert Daten in das angegebene Feld aus einem JSON-Stream, wobei der vollständige Name, der in der Variablen 'fieldFullNameInJSON' angegeben ist, für die Übereinstimmung verwendet wird. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Berechnet alle berechneten Felder im Formular neu. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Setzt die Position des Feldes. |

### Siehe auch

* Klasse [Field](../field/)
* Namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../)