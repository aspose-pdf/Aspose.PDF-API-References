---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.EncryptionOptions-Klasse. Stellt Verschlüsselungsoptionen für das Sicherheits-Plugin dar
type: docs
weight: 8540
url: /de/net/aspose.pdf.plugins/encryptionoptions/
---
## Klasse EncryptionOptions

Stellt Verschlüsselungsoptionen für das [`Security`](../security/) Plugin dar.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Initialisiert eine neue Instanz des `EncryptionOptions`-Objekts mit Standardoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Schließt Eingabeströme nach Abschluss der Operation. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Schließt Ausgabeströme nach Abschluss der Operation. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Kryptografischer Algorithmus, siehe [`CryptoAlgorithm`](./cryptoalgorithm/) für Details. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Dokumentberechtigungen, siehe [`Permissions`](../../aspose.pdf/permissions/) für Details. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Gibt die Datensammlung des OrganizerOptions-Plugins zurück. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Erhält die Sammlung der hinzugefügten Ziele für die Speicherung der Operationsergebnisse. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Besitzerpasswort. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Benutzerpasswort. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Fügt der Datensammlung des PdfOrganizer-Plugins eine neue Datenquelle hinzu. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Fügt der Datensammlung des PdfOrganizer-Plugins eine neue Datenquelle hinzu. |

### Siehe auch

* Klasse [OrganizerBaseOptions](../organizerbaseoptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)