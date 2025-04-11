---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Form-Klasse. Klasse, die das Acro-Form-Objekt darstellt
type: docs
weight: 4290
url: /de/net/aspose.pdf.facades/form/
---
## Formular-Klasse

Klasse, die das Acro-Form-Objekt darstellt.

```csharp
public sealed class Form : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Form](form/#constructor)() | Konstruktor von Form ohne Parameter. |
| [Form](form/#constructor_1)(Document) | Initialisiert ein neues `Form`-Objekt auf Basis des *Dokuments*. |
| [Form](form/#constructor_4)(Stream) | Konstruktor für das Formular. |
| [Form](form/#constructor_7)(string) | Konstruktor von Form. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Setzt das PDF-Dateiformat. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard-PDF-Format ohne Konvertierung gespeichert. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Gibt die Liste der Feldnamen im Formular zurück. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Gibt alle Namen der Formular-Submit-Buttons zurück. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Ergebnis der letzten Importoperation. Array von Objekten, die das Ergebnis des Imports für jedes Feld beschreiben. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Schließt geöffnete Dateien ohne Änderungen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Exportiert den Inhalt der Felder des PDFs in den FDF-Stream. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Exportiert den Inhalt aller Felder im Dokument in einen JSON-Stream. Werte von Button-Feldern werden nicht exportiert. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream. Der Wert des Button-Feldes wird nicht exportiert. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream. Der Wert des Button-Feldes wird nicht exportiert. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Extrahiert das XFA-Datenpaket |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Füllt ein Barcode-Feld gemäß seinem vollqualifizierten Feldnamen. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Füllt das Kontrollkästchenfeld mit einem booleschen Wert. Hinweis: Nur auf Kontrollkästchen anwendbar. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert; Wenn das Feld den vollständigen Namen "Form.Subform.CheckBoxField" hat, sollten Sie den vollständigen Namen angeben und nicht "CheckBoxField". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das erforderliche Feld nach seinem teilweisen Namen zu suchen. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Füllt das Radio-Box-Feld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen. Vor dem Füllen der Felder muss nur der Name des Feldes bekannt sein, während der Wert durch seinen Index angegeben werden kann. Hinweis: Nur auf Radio-Box-, Kombinationsfeld- und Listenfeldfelder anwendbar. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert; Wenn das Feld den vollständigen Namen "Form.Subform.ListBoxField" hat, sollten Sie den vollständigen Namen angeben und nicht "ListBoxField". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das erforderliche Feld nach seinem teilweisen Namen zu suchen. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Füllt das Feld mit einem gültigen Wert gemäß einem vollqualifizierten Feldnamen. Vor dem Füllen der Felder müssen die Namen jedes Feldes und die entsprechenden gültigen Werte bekannt sein. Sowohl die Feldnamen als auch die Werte sind groß- und kleinschreibungsempfindlich. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert; Wenn das Feld den vollständigen Namen "Form.Subform.TextField" hat, sollten Sie den vollständigen Namen angeben und nicht "TextField". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das erforderliche Feld nach seinem teilweisen Namen zu suchen. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Füllt ein Feld mit mehreren Auswahlmöglichkeiten. Hinweis: nur für AcroForm-Listenfeld. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Füllt das Feld mit dem angegebenen Wert. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Füllt die Textfeldfelder mit Textwerten und speichert das Dokument. Relevant für signierte Dokumente. Hinweis: Nur auf Textfelder anwendbar. Sowohl die Feldnamen als auch die Werte sind groß- und kleinschreibungsempfindlich. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Überlädt die Funktion von FillImageField. Der Eingang ist ein Bildstream. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Fügt ein Bild in das vorhandene Buttonfeld als dessen Erscheinungsbild gemäß seinem vollqualifizierten Feldnamen ein. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Flatten alle Felder. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Flatten ein angegebenes Feld mit dem vollqualifizierten Feldnamen. Alle anderen Felder bleiben unveränderlich. Wenn der Feldname ungültig ist, bleiben alle Felder unveränderlich. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Gibt den aktuellen Wert für Radio-Button-Optionsfelder zurück. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Gibt die Radio-Button-Optionsfelder und die zugehörigen Werte basierend auf dem Feldnamen zurück. Diese Methode hat Bedeutung für Radio-Button-Gruppen. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Gibt den Wert des Feldes gemäß seinem Feldnamen zurück. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Gibt das FrofmFieldFacade-Objekt zurück, das alle Erscheinungsattribute enthält. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Gibt die Flags des Feldes zurück. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Gibt die Einschränkung des Textfeldes zurück. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Gibt den Typ des Feldes zurück. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Gibt den vollständigen Feldnamen gemäß seinem kurzen Feldnamen zurück. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Gibt den Wert eines Rich-Text-Feldes zurück, einschließlich der Formatierungsinformationen jedes Zeichens. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Gibt die Übermittlungsflags des Submit-Buttons zurück |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Importiert den Inhalt der Felder aus der FDF-Datei und fügt sie in das neue PDF ein. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Importiert alle Felddaten aus einem JSON-Stream in die Dokumentfelder und ordnet die Felder nach ihren vollständigen Namen zu. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Importiert den Inhalt der Felder aus der XFDF(XML)-Datei und fügt sie in das neue PDF ein. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Importiert den Inhalt der Felder aus der XML-Datei und fügt sie in das neue PDF ein. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Importiert den Inhalt der Felder aus der XML-Datei und fügt sie in das neue PDF ein. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Bestimmt, ob das Feld erforderlich ist oder nicht. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Benennt ein Feld um. Sowohl AcroForm-Feld als auch XFA-Feld sind in Ordnung. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Speichert das Dokument im angegebenen Stream. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Speichert das Dokument in der angegebenen Datei. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Ersetzt die XFA-Daten durch das angegebene Datenpaket. Das Datenpaket kann mit ExtractXfaData extrahiert werden. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Klasse, die das Ergebnis des Feldimports beschreibt. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Status des importierten Feldes |

### Siehe auch

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)