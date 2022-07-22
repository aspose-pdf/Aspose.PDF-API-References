---
title: FormEditor
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse zum Bearbeiten von Formularen Felder hinzufügen/löschen usw.
type: docs
weight: 2340
url: /de/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Klasse zum Bearbeiten von Formularen (Felder hinzufügen/löschen usw.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FormEditor](formeditor#constructor)() | Konstruktor für FormEditor. |
| [FormEditor](formeditor#constructor_1)(Document) | Initialisiert neu[`FormEditor`](../formeditor) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | Ruft den Namen des Anhangs ab oder legt ihn fest, wenn das Ergebnis der Operation als Anhang in HttpResponse-Objekten gespeichert wird. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | Ruft ab oder legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation im HttpResponse-Objekt gespeichert wird. Möglicher Wert: inline / attachment. Standard: inline. |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | Legt das PDF-Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei ohne Konvertierung im Standard-PDF-Format gespeichert. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | Legt Optionen für das Kombinationsfeld mit Exportwerten fest. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | Legt visuelle Attribute des Felds fest. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | Legt Elemente fest, die zu einem neu erstellten Listenfeld oder Kombinationsfeld hinzugefügt werden. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | Ruft die Größe des Radiobutton-Elements ab oder legt sie fest (wenn ein neues Radiobutton-Feld hinzugefügt wird). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | Das Element zum Aufzeichnen des Abstands zwischen zwei benachbarten Optionsfeldern in Pixeln, Standardwert ist 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | Das Flag, das angibt, ob die Funkgeräte horizontal oder vertikal angeordnet sind, der Standardwert ist wahr. |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | Ruft das Antwortobjekt ab oder legt es fest, in dem das Ergebnis der Operation gespeichert wird. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | Ruft Speicheroptionen ab oder legt sie fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | Legen Sie die Submission-Flags der Submit-Schaltfläche fest |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | Feld des angegebenen Typs zum Formular hinzufügen. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | Feld des angegebenen Typs zum Formular hinzufügen. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | Fügen Sie JavaScript für ein PushButton-Feld hinzu. Wenn ein altes Ereignis vorhanden ist, wird danach ein neues Ereignis hinzugefügt. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | Fügt dem Listenfeld ein neues Element hinzu. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | Fügen Sie dem vorhandenen Listenfeld ein neues Element mit Exportwert hinzu, nur für das AcroForm-Kombinationsfeld. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | Senden-Schaltfläche zum Formular hinzufügen. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialisiert die Fassade. |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | Schließt die Fassade. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | Kopiert ein vorhandenes Feld an dieselbe Position in der angegebenen Seitenzahl. Es wird ein neues Dokument erstellt, das alles enthält, was das Quelldokument außer dem neu kopierten Feld enthält. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | Kopiert ein vorhandenes Feld an eine neue Position, die durch Seitenzahl und Ordinaten angegeben wird. Es wird ein neues Dokument erstellt, das alles enthält, was das Quelldokument außer dem neu kopierten Feld enthält. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit Original-Seitenzahl und -Ordinaten. Hinweis: Nur für AcroForm-Felder (außer Radiobox). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitenzahl und Original-Koordinaten. Hinweis: Nur für AcroForm-Felder (außer Radiobox). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitenzahl und Ordinaten. Hinweis: Nur für AcroForm-Felder (außer Radiobox). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | Ändert visuelle Attribute aller Felder im PDF-Dokument. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | Ändert visuelle Attribute aller Felder mit dem angegebenen Feldtyp. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | Ändert visuelle Attribute des angegebenen Felds. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | Artikel aus dem Listenfeld löschen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | Feldflags abrufen. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | Neue Position des Feldes setzen. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | Feld aus dem Formular entfernen. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | Sendeaktion des Felds entfernen. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | Name des Feldes ändern. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | Alle visuellen Attribute auf leeren Wert zurücksetzen. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | Alle visuellen Attribute der Innenfassade auf leeren Wert zurücksetzen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | Legen Sie den Ausrichtungsstil eines Textfelds fest. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | Legen Sie den vertikalen Ausrichtungsstil eines Textfelds fest. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | Feldflags setzen |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | Feldattribute setzen. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | Legt die Anzahl der Kämme für ein reguläres einzeiliges Textfeld fest (das Feld wird automatisch in so viele gleich beabstandete Positionen oder Kämme unterteilt, wie der Wert des Parameters combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | Legt die maximale Zeichenanzahl des Textfelds fest. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | JavaScript für ein PushButton-Feld setzen. Wenn altes JavaScript vorhanden war, wird es durch das neue ersetzt. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | Setze Submit-Flag der Submit-Schaltfläche. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | Legt die URL der Schaltfläche fest. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | Ändern Sie ein einzeiliges Textfeld in ein mehrzeiliges. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
