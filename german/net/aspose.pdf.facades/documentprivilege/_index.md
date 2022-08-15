---
title: DocumentPrivilege
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert die Privilegien für den Zugriff auf die PDF-Datei. Beziehen aufPdfFileSecurity./pdffilesecurity . Es gibt 4 Möglichkeiten diese Klasse zu verwenden 1. Direkte Verwendung vordefinierter Berechtigungen. 2. Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Berechtigungen. 3. Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Adobe Professional-Berechtigungskombinationen. 4.Mischt Weg2 und Weg3.
type: docs
weight: 2240
url: /de/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Repräsentiert die Privilegien für den Zugriff auf die PDF-Datei. Beziehen auf[`PdfFileSecurity`](../pdffilesecurity) . Es gibt 4 Möglichkeiten, diese Klasse zu verwenden: 1. Direkte Verwendung vordefinierter Berechtigungen. 2. Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Berechtigungen. 3. Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Adobe Professional-Berechtigungskombinationen. 4.Mischt Weg2 und Weg3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | Alle erlaubt. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | Ermöglicht das Zusammenbauen der Datei. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | Ermöglicht das Kopieren von Dateien. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | Lässt eingeschränktes Drucken zu. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | Ermöglicht das Ausfüllen von Formularen in der Datei. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | Alles verboten. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | Ermöglicht das Ändern von Anmerkungen der Datei. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | Ermöglicht das Ändern der Datei. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | Ermöglicht das Drucken der Datei. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | Ermöglicht nur das Lesen auf dem Bildschirm. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | Legt die Berechtigung fest, die das Zusammenbauen erlaubt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | Legt die Berechtigung fest, die das Kopieren erlaubt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | Legt die Berechtigung fest, die eingeschränktes Drucken zulässt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | Legt die Berechtigung fest, die das Ausfüllen von Formularen erlaubt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | Legt die Berechtigung fest, die das Ändern von Anmerkungen erlaubt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | Legt die Berechtigung fest, die das Ändern von Inhalten erlaubt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | Legt die Berechtigung fest, die Drucken erlaubt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | Legt die Berechtigung fest, die Screenreader erlaubt oder nicht. wahr ist erlaubt und falsch ist verboten. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | Legt die Änderungsebene der Dokumentberechtigung fest. Genauso wie die Einstellungen „Änderungen zulässig“ von Adobe Professional. 0: Keine. 1: Seiten einfügen, löschen und drehen. 2: Formularfelder ausfüllen und vorhandene Signaturfelder signieren. 3: Kommentieren, Formularfelder ausfüllen und vorhandene signieren Signaturfelder. 4: Beliebig außer Seiten extrahieren. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | Legt die Kopierebene der Dokumentberechtigung fest. Genau wie die Berechtigungseinstellungen von Adobe Professional. 0: Keine. 1: Textzugriff für Bildschirmlesegeräte für Sehbehinderte aktivieren. 2: Kopieren von Text, Bildern und anderen Inhalten aktivieren. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | Legt die Druckebene der Dokumentberechtigung fest. Genau wie die Einstellungen „Drucken erlaubt“ von Adobe Professional. 0: Keine. 1: Niedrige Auflösung (150 dpi). 2: Hohe Auflösung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | Vergleicht zwei[`DocumentPrivilege`](../documentprivilege) Objekte.  Das zu vergleichende Objekt. Eine Ganzzahl mit Vorzeichen, die die relativen Werte dieser Instanz und dieses Werts angibt. Kleiner als Null, diese Instanz ist kleiner als der Wert. Null, diese Instanz ist gleich Wert. Größer als Null, diese Instanz ist größer als der Wert. |

### Beispiele

```csharp
[C#]	
//Way1: Vordefinierte Privilegien direkt verwenden.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Basierend auf einem vordefinierten Privileg und einige spezifische Berechtigungen ändern.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Weg 3: Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Adobe Professional-Berechtigungskombinationen.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Weg4: Mischt Weg2 und Weg3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Vordefinierte Privilegien direkt verwenden.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Basierend auf einem vordefinierten Privileg und ändern Sie einige spezifische Berechtigungen.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Weg 3: Basierend auf einer vordefinierten Berechtigung und Änderung einiger spezifischer Adobe Professional-Berechtigungskombinationen.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mischt way2 und way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Siehe auch

* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
