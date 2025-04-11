---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.EncryptionOptions klass. Representerar krypteringsalternativ för säkerhetsplugin
type: docs
weight: 8540
url: /sv/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions klass

Representerar krypteringsalternativ för [`Security`](../security/) plugin.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Initierar en ny instans av `EncryptionOptions` objektet med standardalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Stänger indataflöden efter att operationen har slutförts. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Stänger utdataflöden efter att operationen har slutförts. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Kryptografisk algoritm, se [`CryptoAlgorithm`](./cryptoalgorithm/) för detaljer. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Dokumentbehörigheter, se [`Permissions`](../../aspose.pdf/permissions/) för detaljer. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Returnerar datainsamling för OrganizerOptions plugin. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Hämtar samling av tillagda mål för att spara operationens resultat. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Ägarens lösenord. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Användarens lösenord. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Lägger till en ny datakälla till PdfOrganizer plugin datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Lägger till en ny datakälla till PdfOrganizer plugin datainsamling. |

### Se Även

* klass [OrganizerBaseOptions](../organizerbaseoptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)