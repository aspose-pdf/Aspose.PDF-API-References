---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Form-Klasse. Klasse, die das Formularobjekt darstellt
type: docs
weight: 5070
url: /de/net/aspose.pdf.forms/form/
---
## Formular-Klasse

Klasse, die das Formularobjekt darstellt.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Wenn gesetzt, werden alle Formularfelder neu berechnet, wenn ein Feld geändert wird. Der Standardwert ist true. Setzen Sie es auf false, um die Leistung beim Ausfüllen von Formularen mit einer großen Anzahl von berechneten Feldern zu erhöhen. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Wenn gesetzt, werden fehlende Formularfelder automatisch erstellt, wenn sie in Anmerkungen vorhanden sind. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Ermöglicht das Festlegen der Reihenfolge der Feldberechnung. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Gibt die Anzahl der Felder in diesem Formular zurück. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Ruft das Standardaussehen des Formulars ab oder setzt es (Objekt, das die Standardschriftart, Textgröße und Farbe für die Felder im Formular beschreibt). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Ruft die Standardressourcen ab, die auf diesem Formular platziert sind. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Wenn diese Eigenschaft true ist, werden zusätzliche rote Randrechtecke für erforderliche Xfa exclGroup-Elementcontainer gezeichnet. Diese Eigenschaft wurde eingeführt, weil es während der Konvertierung von Xfa-Darstellungen von Formularen in den Standard keine Entsprechungen für die exclGroup gab. Sie ist standardmäßig false. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Ruft die Liste aller Felder auf der niedrigsten Ebene des hierarchischen Formulars ab. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Wenn diese Eigenschaft true ist, wird der Wert des NeedsRendering-Schlüssels während der Konvertierung des XFA-Formulars in das Standardformular ignoriert. Sie ist standardmäßig false. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Gibt true zurück, wenn das Objekt threadsicher ist. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Ruft das Feld des Formulars nach Feldnamen ab. Wirft eine Ausnahme, wenn das Feld nicht gefunden wurde. (2 Indizes) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Wenn diese Eigenschaft true ist, wird das "Perms"-Wörterbuch nach der Konvertierung dynamischer Dokumente in den Standard aus dem PDF-Dokument entfernt. Das "Perms"-Wörterbuch kann Regeln enthalten, die die Anzeige der Auswahl von Pflichtfeldern im Adobe Acrobat Reader stören. Sie ist standardmäßig false. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Wenn gesetzt, enthält das Dokument Signaturen, die ungültig werden können, wenn die Datei auf eine Weise gespeichert (geschrieben) wird, die ihren vorherigen Inhalt ändert, im Gegensatz zu einem inkrementellen Update. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Wenn gesetzt, enthält das Dokument mindestens ein Signaturfeld. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Gibt das Synchronisierungsobjekt zurück. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Ruft den Typ des Formulars ab. Mögliche Werte sind: Standard, Statisch, Dynamisch. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Ruft die XFA-Daten des Formulars ab (falls vorhanden). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Fügt ein Feld zum Formular hinzu. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Fügt ein Feld zum Formular hinzu. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Fügt ein neues Feld zum Formular hinzu; Wenn dieses Feld bereits auf einem anderen oder diesem Formular platziert ist, wird eine Kopie des Feldes erstellt. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Fügt das zusätzliche Aussehen des Feldes zur angegebenen Seite des Dokuments an der angegebenen Stelle hinzu. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Setzt das XFA des Formulars auf den angegebenen Wert. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Kopiert die auf dem Formular platzierten Felder in ein Array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Löscht ein Feld aus dem Formular. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Löscht ein Feld aus dem Formular nach seinem Namen. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Exportiert die PDF-Formularfelder in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Exportiert die PDF-Formularfelder in das JSON-Format und schreibt das Ergebnis in die angegebene Datei. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Entfernt alle Formularfelder und platziert deren Werte direkt auf der Seite. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Ruft die Enumeration der Formularfelder ab. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Gibt die Felder innerhalb des angegebenen Rechtecks zurück. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Überprüft, ob das Formular bereits das angegebene Feld hat. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde, mit der Möglichkeit, in die Kinderhierarchie der Felder zu schauen. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importiert die PDF-Formularfelder aus dem im Stream bereitgestellten JSON-Format. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importiert die PDF-Formularfelder aus dem im angegebenen Datei bereitgestellten JSON-Format. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Macht die Anmerkungen der Formularfelder unabhängig. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Entfernt das Aussehen des Feldes am angegebenen Index. Wenn nur ein Kind-Aussehen übrig bleibt, bettet die Methode es in das Feld ein. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Formulare können Signaturinformationen enthalten, d.h. sie können signiert oder unsigniert sein. Und die Ansicht des Formulars muss manchmal davon abhängen, ob das Formular signiert ist oder nicht. Diese Eigenschaft sagt dem Konverter des Formulars (z.B. während der Konvertierung des XFA-Formulars in das Standardformular), ob das resultierende Formular als signiert oder unsigniert gerendert werden muss. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Klasse, die die Einstellungen für das Verfahren zum Flatten von Formularen beschreibt. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Formulare können Signaturinformationen enthalten und können signiert oder unsigniert sein. Manchmal muss die Ansicht von Formularen im Viewer davon abhängen, ob das Formular signiert ist oder nicht. Dieses Enum enumeriert mögliche Render-Modi während der Konvertierung des Formular-Typs in Bezug auf die Signatur. |

### Siehe auch

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)