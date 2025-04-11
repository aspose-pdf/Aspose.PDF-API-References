---
title: Class ComboBoxField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ComboBoxField-Klasse. Klasse, die das Kombinationsfeld des Formulars darstellt
type: docs
weight: 5000
url: /de/net/aspose.pdf.forms/comboboxfield/
---
## ComboBoxField-Klasse

Klasse, die das Kombinationsfeld des Formulars darstellt.

```csharp
public class ComboBoxField : ChoiceField
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ComboBoxField](comboboxfield/#constructor)() | Konstruktor für ComboBoxField, der im Generator verwendet wird. |
| [ComboBoxField](comboboxfield/#constructor_1)(Document) | Erstellt ein Kombinationsfeld, um mit dem Generator zu arbeiten. |
| [ComboBoxField](comboboxfield/#constructor_2)(Document, Rectangle) | Konstruktor für das Kombinationsfeld. |
| [ComboBoxField](comboboxfield/#constructor_3)(Page, Rectangle) | Konstruktor für das Kombinationsfeld. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Ruft die Aktionsannotation ab. (2 Eigenschaften) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ruft den aktuellen Erscheinungszustand der Annotation ab oder legt ihn fest. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Ruft den alternativen Namen des Feldes ab oder legt ihn fest (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens verwendet werden soll, wo immer das Feld in der Benutzeroberfläche identifiziert werden soll). Der alternative Name wird als Feldtooltip in Adobe Acrobat verwendet. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Ruft den Index dieser Annotation auf der Seite ab oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Ruft den Typ der Annotation ab. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ruft die Eigenschaften des Randes der Annotation ab oder legt sie fest. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ruft die Eigenschaften der Annotation ab. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ruft die Farbe der Annotation ab oder legt sie fest. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Ruft das Flag für die sofortige Bestätigung bei Auswahländerung ab oder legt es fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ruft den Text der Annotation ab oder legt ihn fest. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Ruft die Anzahl der Unterfelder in diesem Feld ab. (Zum Beispiel die Anzahl der Elemente im Optionsfeld). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Ruft das Standard-Erscheinungsbild des Feldes ab oder legt es fest. |
| [Editable](../../aspose.pdf.forms/comboboxfield/editable/) { get; set; } | Ruft den bearbeitbaren Status des Feldes ab oder legt ihn fest. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Ruft das exportierbare Flag des Feldes ab oder legt es fest. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ruft den vollqualifizierten Namen der Annotation ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ruft die Höhe der Annotation ab oder legt sie fest. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Hervorhebungsmodus der Annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für den PDF-Generator) ab oder legt ihn fest. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für die PDF-Generierung) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Ruft einen booleschen Wert ab, der angibt, ob dieses Feld ein nicht-terminales Feld ist, d.h. eine Gruppe von Feldern. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist falsch. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für die PDF-Generierung) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld in den Kopf- oder Fußbereich eingefügt wird. Wenn wahr, wird dieses Feld einmal erstellt und sein Erscheinungsbild wird auf allen Seiten des Dokuments sichtbar sein. Wenn falsch, wird für jede Dokumentseite ein separates Feld erstellt. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Gibt true zurück, wenn das Wörterbuch synchronisiert ist. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Ruft das Unterfeld ab, das in diesem Feld nach dem Namen des Unterfeldes enthalten ist. (2 Indizes) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Ruft den Mapping-Namen des Feldes ab oder legt ihn fest, der beim Exportieren interaktiver Formulardaten aus dem Dokument verwendet werden soll. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für die PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ruft das Datum und die Uhrzeit ab oder legt sie fest, wann die Annotation zuletzt geändert wurde. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Ruft das Flag für Mehrfachauswahl ab oder legt es fest. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ruft den Namen der Annotation auf der Seite ab oder legt ihn fest. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Ruft die Sammlung der Auswahloptionen ab. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Ruft den Index der Seite ab, die dieses Feld enthält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Ruft die übergeordnete Annotation ab. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Ruft den Teilnamen des Feldes ab oder legt ihn fest. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Ruft den schreibgeschützten Status des Feldes ab oder legt ihn fest. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Ruft das Rechteck des Feldes ab oder legt es fest. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Ruft den erforderlichen Status des Feldes ab oder legt ihn fest. |
| virtual [Selected](../../aspose.pdf.forms/choicefield/selected/) { get; set; } | Ruft den Index der ausgewählten Option ab oder legt ihn fest. Diese Eigenschaft ermöglicht es, die Auswahl zu ändern. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | Ruft das Array der ausgewählten Elemente ab oder legt es fest. Für die Mehrfachauswahl enthält das Array mehr als ein Element. Für die Einzelauswahl enthält es ein einzelnes Element. |
| [SpellCheck](../../aspose.pdf.forms/comboboxfield/spellcheck/) { get; set; } | Ruft den Status der Rechtschreibprüfung ab oder legt ihn fest. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronisationsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Ruft die Tabulatorreihenfolge des Feldes ab oder legt sie fest. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ruft die Textausrichtung für die Annotation ab oder legt sie fest. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Ruft den Wert des Feldes ab oder legt ihn fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft eine vertikale Ausrichtung des Absatzes ab oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ruft die Breite der Annotation ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Akzeptiert den Besucher. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | Fügt eine neue Option mit dem angegebenen Namen hinzu. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Fügt eine neue Option mit dem angegebenen Exportwert und Namen hinzu. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Löscht die Option nach ihrem Namen. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Führt eine angegebene JavaScript-Aktion für das Feld aus. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in die angegebene Datei. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exportiert den Inhalt des angegebenen Feldes in einen JSON-Stream. Der Wert des Schaltflächenfeldes wird nicht exportiert. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Entfernt dieses Feld und platziert seinen Wert direkt auf der Seite. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Gibt den Namen des "geprüften" Zustands gemäß den vorhandenen Zustandsnamen zurück. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Gibt den Enumerator der enthaltenen Felder zurück. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importiert Daten in die angegebenen Felder aus einem JSON-Stream, basierend auf einer genauen Übereinstimmung der vollständigen Namen der Felder. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importiert Daten in das angegebene Feld aus einem JSON-Stream, wobei der vollständige Name, der in der Variablen 'fieldFullNameInJSON' angegeben ist, für die Übereinstimmung verwendet wird. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Berechnet alle berechneten Felder im Formular neu. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Legt die Position des Feldes fest. |

### Siehe auch

* Klasse [ChoiceField](../choicefield/)
* Namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../)