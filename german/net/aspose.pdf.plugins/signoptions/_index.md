---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.SignOptions-Klasse. Stellt Signaturoptionen für das Signatur-Plugin dar
type: docs
weight: 9250
url: /de/net/aspose.pdf.plugins/signoptions/
---
## SignOptions-Klasse

Stellt Signaturoptionen für das [`Signature`](../signature/) Plugin dar.

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Initialisiert eine neue Instanz des `SignOptions`-Objekts mit Standardoptionen. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Initialisiert eine neue Instanz des `SignOptions`-Objekts mit Standardoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Schließt Eingabeströme nach Abschluss der Operation. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Schließt Ausgabeströme nach Abschluss der Operation. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | Der Kontakt der Signatur. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Gibt die Datensammlung des OrganizerOptions-Plugins zurück. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | Der Standort der Signatur. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | Der Name des vorhandenen Signaturfelds. Null, um ein neues Feld zu erstellen. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Erhält die Sammlung der hinzugefügten Ziele für die Speicherung der Operationsergebnisse. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | Die Seitenzahl, auf der die Signatur erfolgt. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | Der Grund für die Signatur. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | Das Rechteck der Signatur. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | Die Sichtbarkeit der Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Fügt der Datensammlung des PdfOrganizer-Plugins eine neue Datenquelle hinzu. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Fügt der Datensammlung des PdfOrganizer-Plugins eine neue Datenquelle hinzu. |

### Siehe auch

* Klasse [OrganizerBaseOptions](../organizerbaseoptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)