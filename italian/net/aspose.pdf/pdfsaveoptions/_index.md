---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PdfSaveOptions. Opzioni di salvataggio per l'esportazione in formato Pdf
type: docs
weight: 8430
url: /it/net/aspose.pdf/pdfsaveoptions/
---
## Classe PdfSaveOptions

Opzioni di salvataggio per l'esportazione in formato Pdf

```csharp
public class PdfSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da pdf ad altri formati, ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Nome del font utilizzato per impostazione predefinita per i font assenti sul computer. Quando il documento PDF salvato contiene font che non sono disponibili nel documento stesso e sul dispositivo, l'API sostituisce questi font con il font predefinito (se il font con [`DefaultFontName`](./defaultfontname/) è trovato sul dispositivo) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Percorso per i file temporanei. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di salvataggio dovrebbe cessare. |

## Esempi

Il seguente esempio mostra come impostare il nome del font predefinito durante il salvataggio del PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Load an existing PDF document with missing font
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Specify Default Font Name
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### Vedi Anche

* classe [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)