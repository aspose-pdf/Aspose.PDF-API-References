---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.EncryptionOptions. Rappresenta le opzioni di crittografia per il plugin di sicurezza
type: docs
weight: 8540
url: /it/net/aspose.pdf.plugins/encryptionoptions/
---
## Classe EncryptionOptions

Rappresenta le opzioni di crittografia per il plugin [`Security`](../security/).

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Inizializza una nuova istanza dell'oggetto `EncryptionOptions` con opzioni predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Chiude i flussi di input dopo il completamento dell'operazione. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Chiude i flussi di output dopo il completamento dell'operazione. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Algoritmo crittografico, vedere [`CryptoAlgorithm`](./cryptoalgorithm/) per dettagli. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Permessi del documento, vedere [`Permissions`](../../aspose.pdf/permissions/) per dettagli. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Ottiene la raccolta degli obiettivi aggiunti per salvare i risultati dell'operazione. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Password del proprietario. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Password dell'utente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin PdfOrganizer. |

### Vedi Anche

* classe [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)