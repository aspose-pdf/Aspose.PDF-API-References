---
title: "Klass EncryptionOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.EncryptionOptions-klass. Representerar krypteringsalternativ för Security-plugin."
type: docs
weight: 8670
url: /sv/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

Representerar krypteringsalternativ för [`Security`](../security/)-plugin.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Initierar en ny instans av `EncryptionOptions`-objektet med standardalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Stäng inmatningsströmmar när operationen är slutförd. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Stäng utmatningsströmmar när operationen är slutförd. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Kryptografisk algoritm, se [`CryptoAlgorithm`](./cryptoalgorithm/) för detaljer. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Document permissions, se [`Permissions`](../../aspose.pdf/permissions/) för detaljer. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Returnerar data-samlingen för OrganizerOptions-pluginen. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Hämtar samlingen av tillagda mål för att spara resultat av operationen. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Ägarlösenord. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Användarlösenord. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Lägger till en ny datakälla i PdfOrganizer-pluginens datasamling. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Lägger till en ny datakälla i PdfOrganizer-pluginens datasamling. |

### Se även

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


