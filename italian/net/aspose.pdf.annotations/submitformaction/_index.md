---
title: "Classe SubmitFormAction"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Annotations.SubmitFormAction. Classe che descrive l'azione submitform."
type: docs
weight: 2740
url: /it/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

Classe che descrive l'azione submit-form.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Inizializza l'oggetto SubmitFormAction. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Ottiene o imposta i flag dell'azione di submit. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Azioni successive nella sequenza. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | URL di destinazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Ottiene la stringa per l'Azione ECMAScript. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Se impostato, tutti i valori dei campi inviati che rappresentano date saranno convertiti nel formato standard. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Se impostato, la voce F del FDF inviato deve essere una specifica di file contenente un flusso di file incorporato che rappresenta il file PDF da cui il FDF viene inviato. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Se impostato, il FDF inviato deve escludere la voce F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Se impostato, includerà solo quelle annotazioni markup la cui voce T corrisponde al nome dell'utente corrente. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Se cancellato, l'array Fields specifica quali campi includere nella sottomissione. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Se impostato, i nomi dei campi e i valori saranno inviati in formato HTML Form. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Se impostato, i nomi dei campi e i valori saranno inviati tramite una richiesta HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Se impostato, il file FDF inviato includerà tutte le annotazioni di markup nel documento PDF sottostante. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Se impostato, il file FDF inviato includerà il contenuto di tutti gli aggiornamenti incrementali. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Se impostato, tutti i campi designati dall'array Fields e dal flag Include/Exclude saranno inviati. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Se impostato, le coordinate del clic del mouse che ha causato l'azione submit-form saranno trasmesse come parte dei dati del modulo. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Se impostato, il documento sarà inviato come PDF, utilizzando il tipo di contenuto MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Se impostato, i nomi dei campi e i valori saranno inviati come XFDF. |

### Vedi anche

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


