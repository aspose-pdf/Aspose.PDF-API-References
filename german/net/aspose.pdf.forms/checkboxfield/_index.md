---
title: Class CheckboxField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.CheckboxField-Klasse. Klasse, die ein Kontrollkästchenfeld darstellt
type: docs
weight: 4980
url: /de/net/aspose.pdf.forms/checkboxfield/
---
## CheckboxField-Klasse

Klasse, die ein Kontrollkästchenfeld darstellt

```csharp
public class CheckboxField : Field
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CheckboxField](checkboxfield/#constructor_1)(Document) | Konstruktor zur Verwendung mit Generator. |
| [CheckboxField](checkboxfield/#constructor_2)(Document, Rectangle) | Konstruktor für die CheckboxField-Klasse. |
| [CheckboxField](checkboxfield/#constructor_3)(Page, Rectangle) | Konstruktor für die CheckboxField-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Ruft die Aktionsannotation ab. (2 Eigenschaften) |
| override [ActiveState](../../aspose.pdf.forms/checkboxfield/activestate/) { get; set; } | Ruft den aktuellen Erscheinungszustand der Annotation ab oder legt ihn fest. |
| [AllowedStates](../../aspose.pdf.forms/checkboxfield/allowedstates/) { get; } | Gibt die Liste der erlaubten Zustände zurück. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Ruft den alternativen Namen des Feldes ab oder legt ihn fest (Ein alternativer Feldname, der anstelle des tatsächlichen Feldnamens verwendet werden soll, wo immer das Feld in der Benutzeroberfläche identifiziert werden soll). Der alternative Name wird als Feldtooltip in Adobe Acrobat verwendet. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Ruft den Index dieser Annotation auf der Seite ab oder legt ihn fest. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Ruft den Typ der Annotation ab. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ruft die Eigenschaften des Randes der Annotation ab oder legt sie fest. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ruft die Eigenschaften der Annotation ab. |
| [Checked](../../aspose.pdf.forms/checkboxfield/checked/) { get; set; } | Ruft den Zustand des Kontrollkästchens ab oder legt ihn fest. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ruft die Farbe der Annotation ab oder legt sie fest. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ruft den Text der Annotation ab oder legt ihn fest. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Ruft die Anzahl der Unterfelder in diesem Feld ab. (Zum Beispiel die Anzahl der Elemente im Optionsfeld). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Ruft das Standard-Erscheinungsbild des Feldes ab oder legt es fest. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Ruft das exportierbare Flag des Feldes ab oder legt es fest. |
| [ExportValue](../../aspose.pdf.forms/checkboxfield/exportvalue/) { get; set; } | Ruft den Exportwert des Kontrollkästchenfeldes ab oder legt ihn fest. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags der Annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ruft den vollqualifizierten Namen der Annotation ab. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ruft die Höhe der Annotation ab oder legt sie fest. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Hervorhebungsmodus der Annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink ab oder legt ihn fest (für PDF-Generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist falsch. (für PDF-Generierung) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieses Feld ein nicht-terminales Feld ist, d.h. eine Gruppe von Feldern. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft einen Absatz ab oder legt ihn fest, der inline ist. Standard ist falsch. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist falsch. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für PDF-Generierung) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld in den Kopf- oder Fußbereich eingefügt wird. Wenn wahr, wird dieses Feld einmal erstellt und sein Erscheinungsbild wird auf allen Seiten des Dokuments sichtbar sein. Wenn falsch, wird für jede Dokumentseite ein separates Feld erstellt. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Gibt true zurück, wenn das Wörterbuch synchronisiert ist. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Ruft das Unterfeld ab, das in diesem Feld nach dem Namen des Unterfeldes enthalten ist. (2 Indizes) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Ruft den Mapping-Namen des Feldes ab oder legt ihn fest, der beim Exportieren von interaktiven Formulardaten aus dem Dokument verwendet werden soll. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für PDF-Generierung) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ruft das Datum und die Uhrzeit ab oder legt sie fest, wann die Annotation zuletzt geändert wurde. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ruft den Namen der Annotation auf der Seite ab oder legt ihn fest. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Eine Aktion, die ausgeführt werden soll, wenn die Annotation aktiviert wird. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Ruft den Index der Seite ab, die dieses Feld enthält. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Ruft den übergeordneten Annotation ab. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Ruft den teilweisen Namen des Feldes ab oder legt ihn fest. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Ruft den schreibgeschützten Status des Feldes ab oder legt ihn fest. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Ruft das Rechteck des Feldes ab oder legt es fest. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Ruft den erforderlichen Status des Feldes ab oder legt ihn fest. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ruft das Erscheinungsbild-Wörterbuch der Annotation ab. |
| [Style](../../aspose.pdf.forms/checkboxfield/style/) { get; set; } | Ruft den Stil des Kontrollkästchens ab oder legt ihn fest. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronisationsobjekt. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Ruft die Tabulatorreihenfolge des Feldes ab oder legt sie fest. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ruft die Textausrichtung für die Annotation ab oder legt sie fest. |
| override [Value](../../aspose.pdf.forms/checkboxfield/value/) { get; set; } | Ruft den Wert des Kontrollkästchenfeldes ab oder legt ihn fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft eine vertikale Ausrichtung des Absatzes ab oder legt sie fest. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ruft die Breite der Annotation ab oder legt sie fest. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Akzeptiert den Besucher. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption)(string) | Fügt eine neue Checkbox in eine Checkbox-Gruppe ein, in der höchstens eine der Checkboxen zu einem Zeitpunkt aktiviert sein kann. Die neue Checkbox wird am Ende der Gruppe hinzugefügt. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_1)(string, Rectangle) | Fügt eine neue Checkbox in eine Checkbox-Gruppe ein, in der höchstens eine der Checkboxen zu einem Zeitpunkt aktiviert sein kann. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_2)(string, int, Rectangle) | Fügt eine neue Checkbox in eine Checkbox-Gruppe ein, in der höchstens eine der Checkboxen zu einem Zeitpunkt aktiviert sein kann. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| override [Clone](../../aspose.pdf.forms/checkboxfield/clone/)() | Klont das Kontrollkästchen. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Kopiert Unterfelder dieses Feldes in ein Array, beginnend ab dem angegebenen Index. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Führt eine angegebene JavaScript-Aktion für das Feld aus. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in die angegebene Datei. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exportiert den Inhalt des angegebenen Feldes in einen JSON-Stream. Werte von Schaltflächenfeldern werden nicht exportiert. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Entfernt dieses Feld und platziert seinen Wert direkt auf der Seite. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Gibt den Namen des "aktivierten" Zustands gemäß den vorhandenen Zustandsnamen zurück. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Gibt den Enumerator der enthaltenen Felder zurück. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Gibt das Rechteck der Annotation unter Berücksichtigung der Seitenrotation zurück. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importiert Daten in die angegebenen Felder aus einem JSON-Stream, basierend auf einer genauen Übereinstimmung der vollständigen Namen der Felder. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importiert Daten in das angegebene Feld aus einem JSON-Stream, wobei der vollständige Name, der in der Variablen 'fieldFullNameInJSON' angegeben ist, für die Übereinstimmung verwendet wird. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Berechnet alle berechneten Felder im Formular neu. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Setzt die Position des Feldes. |

## Beispiele

Das Beispiel zeigt, wie man ein Mehrwert-Kontrollkästchenfeld erstellt.

```csharp
using (var document = new Document())
{
var page = document.Pages.Add();

var checkbox = new CheckboxField(page, new Rectangle(50, 50, 70, 70));

// Set the first checkbox group option value
checkbox.ExportValue = "option 1";

// Add new option right under existing ones
checkbox.AddOption("option 2");

// Add new option at the given rectangle
checkbox.AddOption("option 3", new Rectangle(100, 100, 120, 120));

document.Form.Add(checkbox);

// Select the added checkbox
checkbox.Value = "option 2";
document.Save("checkbox_group.pdf");
}
```

### Siehe auch

* Klasse [Field](../field/)
* Namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../)