---
title: Form
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse die das Formularobjekt darstellt.
type: docs
weight: 3020
url: /de/net/aspose.pdf.forms/form/
---
## Form class

Klasse, die das Formularobjekt darstellt.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | Wenn gesetzt, werden alle Formularfelder neu berechnet, wenn ein Feld geändert wird. Der Standardwert ist wahr. Auf „false“ setzen, um die Leistung beim Ausfüllen von Formularen mit einer großen Anzahl berechneter Felder zu erhöhen. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | Wenn festgelegt, werden fehlende Formularfelder automatisch erstellt, wenn sie in Anmerkungen vorhanden sind. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Ermöglicht das Festlegen der Reihenfolge der Feldberechnung. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Ruft die Anzahl der Felder in diesem Formular ab. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Ruft die Standarddarstellung des Formulars ab oder legt sie fest (Objekt, das die Standardschriftart, -textgröße und -farbe für Felder im Formular beschreibt). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Ruft Standardressourcen ab, die auf diesem Formular platziert sind. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | Wenn diese Eigenschaft wahr ist, werden zusätzliche rote Begrenzungsrechtecke für erforderliche Xfa exclGroup-Elemente container gezeichnet. Diese Eigenschaft wurde eingeführt, weil Analoga für die exclGroup während der Konvertierung der Xfa-Darstellung von Formularen in Standard. fehlen. Sie ist standardmäßig falsch. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | Ruft eine Liste aller Felder in der untersten Ebene der hierarchischen Form ab. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | Wenn diese Eigenschaft wahr ist, wird der Wert des NeedsRendering-Schlüssels während der Konvertierung des XFA-Formulars in das Standardformular ignoriert. Es ist standardmäßig falsch. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Gibt wahr zurück, wenn das Objekt Thread-sicher ist. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Ruft das Feld des Formulars nach Feldname ab. Löst eine Ausnahme aus, wenn das Feld nicht gefunden wurde. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | Wenn diese Eigenschaft wahr ist, wird das "Perms"-Wörterbuch aus dem PDF-Dokument entfernt, nachdem dynamische Dokumente in Standard umgewandelt wurden. Das „Perms“-Wörterbuch kann Regeln enthalten, die die Anzeige der Auswahl von Pflichtfeldern im Adobe Acrobat Reader stören. Es ist standardmäßig falsch. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | Wenn gesetzt, enthält das Dokument Signaturen, die ungültig werden können, wenn die Datei auf eine Weise gespeichert (geschrieben) wird, die ihren vorherigen Inhalt verändert, im Gegensatz zu einer inkrementellen Aktualisierung. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | Wenn gesetzt, enthält das Dokument mindestens ein Signaturfeld. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Gibt das Synchronisationsobjekt zurück. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Ruft den Typ des Formulars ab. Mögliche Werte sind: Standard, Statisch, Dynamisch. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Ruft XFA-Daten des Formulars ab (falls vorhanden). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Fügt dem Formular ein Feld hinzu. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Fügt dem Formular ein Feld hinzu. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Fügt dem Formular ein neues Feld hinzu; Wenn dieses Feld bereits auf einem anderen oder diesem Formular platziert ist, wird die Kopie des Felds erstellt. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Fügt der angegebenen Seite des Dokuments an der angegebenen Stelle ein zusätzliches Erscheinungsbild des Felds hinzu. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Setzt XFA des Formulars auf den angegebenen Wert. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Kopiert auf dem Formular platzierte Felder in ein Array. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Feld aus dem Formular löschen. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Löscht das Feld nach seinem Namen aus dem Formular. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Entfernt alle Formularfelder und platziert ihre Werte direkt auf der Seite. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Ruft die Aufzählung von Formularfeldern ab. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Gibt Felder innerhalb des angegebenen Rechtecks zurück. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Überprüfen Sie, ob das Formular bereits ein bestimmtes Feld hat. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | Formulare können Signaturinformationen enthalten, dh können signiert oder unsigniert sein. Und die Formularansicht muss manchmal davon abhängen, ob das Formular signiert ist oder nicht. Diese Eigenschaft teilt dem Konverter des Formulars mit (zB während der Konvertierung des XFA-Formulars in das Standardformular) , ob das Ergebnisformular vorliegt muss als signiert oder als unsigniert gerendert werden. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Klasse, die Einstellungen für die Form-Flattening-Prozedur beschreibt. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | Formulare können Signaturinformationen enthalten und können signiert oder unsigniert sein. Manchmal muss die Ansicht von Formularen im Viewer davon abhängen, ob das Formular signiert ist oder nicht. Diese Aufzählung listet mögliche Darstellungsmodi während der Konvertierung des Formulartyps in Bezug auf das Signieren auf. |

### Siehe auch

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* namensraum [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
