---
title: "Classe EncryptionOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.EncryptionOptions. Rappresenta le Opzioni di Cifratura per il plugin Security"
type: docs
weight: 8670
url: /it/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

Rappresenta le Opzioni di Cifratura per il plugin [`Security`](../security/).

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Inizializza una nuova istanza dell'oggetto `EncryptionOptions` con le opzioni predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Chiudi i flussi di input dopo il completamento dell'operazione. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Chiudi i flussi di output dopo il completamento dell'operazione. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Algoritmo crittografico, vedere [`CryptoAlgorithm`](./cryptoalgorithm/) per i dettagli. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Autorizzazioni del documento, vedere [`Permissions`](../../aspose.pdf/permissions/) per i dettagli. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Restituisce la raccolta dati del plugin OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Ottiene la raccolta dei target aggiunti per salvare i risultati dell'operazione. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Password del proprietario. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Password utente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Aggiunge una nuova origine dati alla raccolta dati del plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Aggiunge una nuova origine dati alla raccolta dati del plugin PdfOrganizer. |

### Vedi anche

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


