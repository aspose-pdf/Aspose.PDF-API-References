---
title: Form
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse die das Acro-Formularobjekt darstellt.
type: docs
weight: 2300
url: /de/net/aspose.pdf.facades/form/
---
## Form class

Klasse, die das Acro-Formularobjekt darstellt.

```csharp
public sealed class Form : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Form](form#constructor)() | Konstruktor des Formulars ohne Parameter. |
| [Form](form#constructor_1)(Document) | Initialisiert neu[`Form`](../form) Objekt auf Basis der*document* . |
| [Form](form#constructor_4)(Stream) | Konstruktor für Formular. |
| [Form](form#constructor_8)(string) | Konstruktor von Form. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | Ruft den Namen des Anhangs ab oder legt ihn fest, wenn das Ergebnis der Operation als Anhang in HttpResponse-Objekten gespeichert wird. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | Ruft ab oder legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation im HttpResponse-Objekt gespeichert wird. Möglicher Wert: inline / attachment. Standard: inline. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | Legt das PDF-Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei ohne Konvertierung im Standard-PDF-Format gespeichert. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | Ruft eine Liste mit Feldnamen im Formular ab. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | Ruft alle Namen der Schaltfläche zum Senden des Formulars ab. |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | Ergebnis des letzten Importvorgangs. Array von Objekten, die das Ergebnis des Imports für jedes Feld beschreiben. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | Ruft das Antwortobjekt ab oder legt es fest, in dem das Ergebnis der Operation gespeichert wird. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | Ruft Speicheroptionen ab oder legt sie fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialisiert die Fassade. |
| override [Close](../../aspose.pdf.facades/form/close)() | Schließt geöffnete Dateien ohne Änderungen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | Exportiert den Inhalt der Felder des pdf in den fdf-Stream. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | Exportiert den Inhalt der Felder des PDF in den XML-Stream. Der Wert des Schaltflächenfelds wird nicht exportiert. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | Exportiert den Inhalt der Felder des PDF in den XML-Stream. Der Wert des Schaltflächenfelds wird nicht exportiert. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | Extrahiert XFA-Datenpaket |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | Füllen Sie ein Barcode-Feld gemäß seinem vollständig qualifizierten Feldnamen aus. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | Füllt das Kontrollkästchenfeld mit einem booleschen Wert. Hinweis: Nur auf Kontrollkästchen anwenden. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf nicht mit teilweisen Feldnamen arbeitet .Kit; Wenn das Feld beispielsweise den vollständigen Namen „Form.Subform.CheckBoxField“ hat, sollten Sie den vollständigen Namen und nicht „CheckBoxField“ angeben. Sie können die FieldNames-Eigenschaft verwenden, um vorhandene Feldnamen zu durchsuchen und das erforderliche Feld anhand seines Teilnamens zu suchen. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | Füllt das Radiobox-Feld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen. Vor dem Füllen der Felder muss nur der Feldname bekannt sein. Während der Wert durch seinen Index angegeben werden kann. Hinweis: Nur auf Radio Box-, Combo Box- und List Box-Felder anwenden. Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit unvollständigen -Feldnamen arbeitet im Gegensatz zu Aspose.Pdf.Kit; Wenn das Feld beispielsweise den vollständigen Namen "Form.Subform.ListBoxField" hat, sollten Sie den vollständigen Namen und nicht "ListBoxField" angeben. Sie können die FieldNames-Eigenschaft verwenden, um vorhandene Feldnamen zu durchsuchen und das erforderliche Feld anhand seines Teilnamens zu durchsuchen. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | Füllt das Feld mit einem gültigen Wert gemäß einem vollständig qualifizierten Feldnamen. Vor dem Ausfüllen der Felder müssen die Namen aller Felder und die entsprechenden gültigen Werte bekannt sein. Bei Feldnamen und -werten wird zwischen Groß- und Kleinschreibung unterschieden. Bitte beachten Sie dies Aspose.Pdf.Facades unterstützt nur vollständige Feldnamen und arbeitet nicht mit teilweisen Feldnamen im Gegensatz zu Aspose.Pdf.Kit; Wenn das Feld beispielsweise den vollständigen Namen "Form.Subform.TextField" hat, sollten Sie den vollständigen Namen angeben und nicht "Textfeld". Sie können die FieldNames-Eigenschaft verwenden, um vorhandene Feldnamen zu durchsuchen und das erforderliche Feld anhand seines Teilnamens zu durchsuchen. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | Füllen Sie ein Feld mit Mehrfachauswahl.Hinweis: nur für AcroForm List Box Field. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | Füllt das Feld mit dem angegebenen Wert. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | Füllt die Textfeldfelder mit Textwerten aus und speichert das Dokument. Relevant für signierte Dokumente. Hinweis: Nur auf Textfeld anwenden. Sowohl der Feldname als auch die Werte sind zwischen Groß- und Kleinschreibung zu unterscheiden. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | Überlädt die Funktion von FillImageField. Die Eingabe ist ein Bildstream. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | Fügt ein Bild gemäß seines vollqualifizierten Feldnamens in das vorhandene Schaltflächenfeld als Aussehen ein. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | Flacht alle Felder ab. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | Flacht ein angegebenes Feld mit dem vollständig qualifizierten Feldnamen ab. Alle anderen Felder bleiben unverändert. Wenn der fieldName ungültig ist, bleiben alle Felder unveränderlich. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | Gibt den aktuellen Wert für Optionsfelder für Optionsfelder zurück. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | Ruft Optionsfelder für Optionsfelder und zugehörige Werte basierend auf dem Feldnamen ab. Diese Methode hat Bedeutung für Gruppen von Optionsfeldern. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | Ruft den Wert des Felds gemäß seinem Feldnamen ab. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | Gibt das FrommFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | Gibt Flags des Feldes zurück. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | Holen Sie sich die Begrenzung des Textfelds. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | Gibt den Feldtyp zurück. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | Ruft den vollständigen Feldnamen gemäß seinem kurzen Feldnamen ab. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | Ruft den Wert eines Rich-Text-Felds ab, einschließlich der Formatinformationen für jedes Zeichen. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | Gibt die Submission-Flags der Submit-Schaltfläche zurück |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | Importiert den Inhalt der Felder aus der fdf-Datei und fügt sie in das neue pdf ein. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und fügt sie in das neue pdf ein. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | Importiert den Inhalt der Felder aus der xml-Datei und fügt sie in das neue pdf ein. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | Importiert den Inhalt der Felder aus der xml-Datei und fügt sie in das neue pdf ein. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | Legt fest, ob das Feld erforderlich ist oder nicht. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | Benennt ein Feld um. Entweder das AcroForm-Feld oder das XFA-Feld ist in Ordnung. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | Speichert das Dokument im angegebenen Stream. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | Speichert das Dokument in der angegebenen Datei. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | Ersetzt XFA-Daten durch angegebenes Datenpaket. Datenpakete können mit ExtractXfaData extrahiert werden. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [FormImportResult](form.formimportresult) | Klasse, die das Ergebnis beim Feldimport beschreibt. |
| enum [ImportStatus](form.importstatus) | Status des importierten Felds |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
