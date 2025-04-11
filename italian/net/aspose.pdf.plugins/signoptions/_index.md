---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.SignOptions. Rappresenta le opzioni di firma per il plugin di firma
type: docs
weight: 9250
url: /it/net/aspose.pdf.plugins/signoptions/
---
## Classe SignOptions

Rappresenta le opzioni di firma per il plugin [`Signature`](../signature/).

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Inizializza una nuova istanza dell'oggetto `SignOptions` con opzioni predefinite. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Inizializza una nuova istanza dell'oggetto `SignOptions` con opzioni predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Chiude i flussi di input dopo il completamento dell'operazione. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Chiude i flussi di output dopo il completamento dell'operazione. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | Il contatto della firma. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin OrganizerOptions. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | La posizione della firma. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | Il nome del campo di firma esistente. Null per creare un nuovo campo. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Ottiene la raccolta degli obiettivi aggiunti per salvare i risultati dell'operazione. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | Il numero di pagina su cui è effettuata la firma. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | Il motivo della firma. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | Il rettangolo della firma. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | La visibilità della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin PdfOrganizer. |

### Vedi Anche

* classe [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)