---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.DocumentPrivilege-Klasse. Stellt die Berechtigungen für den Zugriff auf Pdf-Dateien dar. Siehe PdfFileSecurity. Es gibt 4 Möglichkeiten, diese Klasse zu verwenden: 1. Verwendung vordefinierter Berechtigungen direkt. 2. Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Berechtigungen. 3. Basierend auf einer vordefinierten Berechtigung und Änderung einer Kombination spezifischer Adobe Professional-Berechtigungen. 4. Mischt die Methode 2 und Methode 3.
type: docs
weight: 4230
url: /de/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege-Klasse

Stellt die Berechtigungen für den Zugriff auf Pdf-Dateien dar. Siehe [`PdfFileSecurity`](../pdffilesecurity/). Es gibt 4 Möglichkeiten, diese Klasse zu verwenden: 1. Verwendung vordefinierter Berechtigungen direkt. 2. Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Berechtigungen. 3. Basierend auf einer vordefinierten Berechtigung und Änderung einer Kombination spezifischer Adobe Professional-Berechtigungen. 4. Mischt die Methode 2 und Methode 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Alle erlaubt. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Erlaubt das Zusammenstellen von Dateien. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Erlaubt das Kopieren von Dateien. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Erlaubt degradierte Druckausgaben. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Erlaubt das Ausfüllen von Formularen in der Datei. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Alle verboten. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Erlaubt das Ändern von Annotationen der Datei. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Erlaubt das Ändern der Datei. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Erlaubt das Drucken der Datei. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Erlaubt nur das Lesen auf dem Bildschirm. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Legt die Berechtigung fest, die das Zusammenstellen erlaubt oder nicht. true erlaubt und false verbietet. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Legt die Berechtigung fest, die das Kopieren erlaubt oder nicht. true erlaubt und false verbietet. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Legt die Berechtigung fest, die degradierte Druckausgaben erlaubt oder nicht. true erlaubt und false verbietet. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Legt die Berechtigung fest, die das Ausfüllen von Formularen erlaubt oder nicht. true erlaubt und false verbietet. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Legt die Berechtigung fest, die das Ändern von Annotationen erlaubt oder nicht. true erlaubt und false verbietet. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Legt die Berechtigung fest, die das Ändern von Inhalten erlaubt oder nicht. true erlaubt und false verbietet. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Legt die Berechtigung fest, die das Drucken erlaubt oder nicht. true erlaubt und false verbietet. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Legt die Berechtigung fest, die Bildschirmlesegeräte erlaubt oder nicht. true erlaubt und false verbietet. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Ruft das Änderungsniveau der Berechtigungen des Dokuments ab und legt es fest. Entspricht den Einstellungen „Änderungen erlaubt“ von Adobe Professional. 0: Keine. 1: Einfügen, Löschen und Drehen von Seiten. 2: Ausfüllen von Formularfeldern und Unterzeichnen vorhandener Unterschriftsfelder. 3: Kommentieren, Ausfüllen von Formularfeldern und Unterzeichnen vorhandener Unterschriftsfelder. 4: Alles außer dem Extrahieren von Seiten. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Ruft das Kopierniveau der Berechtigungen des Dokuments ab und legt es fest. Entspricht den Berechtigungseinstellungen von Adobe Professional. 0: Keine. 1: Aktiviert den Textzugriff für Bildschirmlesegeräte für sehbehinderte Personen. 2: Aktiviert das Kopieren von Text, Bildern und anderen Inhalten. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Ruft das Druckniveau der Berechtigungen des Dokuments ab und legt es fest. Entspricht den Einstellungen „Drucken erlaubt“ von Adobe Professional. 0: Keine. 1: Niedrige Auflösung (150 dpi). 2: Hohe Auflösung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Vergleicht zwei `DocumentPrivilege`-Objekte. Das Objekt, mit dem verglichen werden soll. Ein vorzeichenbehafteter Integer, der die relativen Werte dieser Instanz und des Wertes angibt. Weniger als null, diese Instanz ist kleiner als der Wert. Null, diese Instanz ist gleich dem Wert. Größer als null, diese Instanz ist größer als der Wert. |

## Beispiele

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Siehe auch

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)