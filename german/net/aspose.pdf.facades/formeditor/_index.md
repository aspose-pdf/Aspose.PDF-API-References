---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormEditor-Klasse. Klasse zum Bearbeiten von Formularen, Hinzufügen/Löschen von Feldern usw.
type: docs
weight: 4330
url: /de/net/aspose.pdf.facades/formeditor/
---
## FormEditor-Klasse

Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Konstruktor für FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Initialisiert ein neues `FormEditor`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Legt das PDF-Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard-PDF-Format ohne Konvertierung gespeichert. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ruft das Dokument ab, an dem die Fassade arbeitet. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Legt die Optionen für das Kombinationsfeld mit Exportwerten fest. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Legt die visuellen Attribute des Feldes fest. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Legt die Elemente fest, die zur neu erstellten Listbox oder zum Kombinationsfeld hinzugefügt werden. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Ruft die Größe des Radio-Button-Elements ab oder legt sie fest (wenn ein neues Radio-Button-Feld hinzugefügt wird). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Das Mitglied zur Aufzeichnung des Abstands zwischen zwei benachbarten Radio-Buttons in Pixeln, Standardwert ist 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Das Flag, um anzuzeigen, ob die Radios horizontal oder vertikal angeordnet sind, Standardwert ist true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Legt die Übermittlungsflags des Submit-Buttons fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Fügt JavaScript für ein PushButton-Feld hinzu. Wenn ein altes Ereignis vorhanden ist, wird das neue Ereignis danach hinzugefügt. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Fügt ein neues Element zur Listbox hinzu. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Fügt ein neues Element mit Exportwert zum vorhandenen Listbox-Feld hinzu, nur für AcroForm-Kombinationsfeld. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Fügt einen Submit-Button zum Formular hinzu. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Schließt die Fassade. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Kopiert ein vorhandenes Feld an die gleiche Position in der angegebenen Seitenzahl. Ein neues Dokument wird erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitenzahl als auch durch die Koordinaten angegeben wird. Ein neues Dokument wird erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit der ursprünglichen Seitenzahl und den Koordinaten. Hinweis: Nur für AcroForm-Felder (außer Radio-Box). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit der angegebenen Seitenzahl und den ursprünglichen Koordinaten. Hinweis: Nur für AcroForm-Felder (außer Radio-Box). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit der angegebenen Seitenzahl und den Koordinaten. Hinweis: Nur für AcroForm-Felder (außer Radio-Box). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Ändert die visuellen Attribute aller Felder im PDF-Dokument. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Ändert die visuellen Attribute aller Felder mit dem angegebenen Feldtyp. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Ändert die visuellen Attribute des angegebenen Feldes. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Löscht ein Element aus dem Listenfeld. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Ruft die Feldflags ab. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Legt die neue Position des Feldes fest. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Entfernt ein Feld aus dem Formular. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Entfernt die Übermittlungsaktion des Feldes. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Ändert den Namen des Feldes. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Setzt alle visuellen Attribute auf leere Werte zurück. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Setzt alle visuellen Attribute der inneren Fassade auf leere Werte zurück. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Legt den Ausrichtungsstil eines Textfeldes fest. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Legt den vertikalen Ausrichtungsstil eines Textfeldes fest. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Legt die Feldflags fest. |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Legt die Attribute des Feldes fest. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Legt die Anzahl der Comb für ein reguläres einzeiliges Textfeld fest (das Feld wird automatisch in so viele gleichmäßig verteilte Positionen oder Comb unterteilt, wie der Wert des Parameters combNumber angibt). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Legt die maximale Zeichenanzahl des Textfeldes fest. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Legt JavaScript für ein PushButton-Feld fest. Wenn altes JavaScript vorhanden ist, wird es durch das neue ersetzt. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Legt das Übermittlungsflag des Submit-Buttons fest. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Legt die URL des Buttons fest. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Ändert ein einzeiliges Textfeld in ein mehrzeiliges. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)