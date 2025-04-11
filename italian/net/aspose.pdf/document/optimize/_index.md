---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Metodo Document. Linearizza il documento per aprire la prima pagina il più rapidamente possibile, visualizzare la pagina successiva o seguire il link alla pagina successiva il più rapidamente possibile, visualizzare la pagina in modo incrementale man mano che arriva quando i dati per una pagina vengono consegnati su un canale lento, visualizzare prima i dati più utili, consentire l'interazione dell'utente, come seguire un link, anche prima che l'intera pagina sia stata ricevuta e visualizzata. Invocare questo metodo non salva effettivamente il documento. Al contrario, il documento è solo preparato per avere una struttura ottimizzata, quindi chiama Salva per ottenere il documento ottimizzato.
type: docs
weight: 750
url: /it/net/aspose.pdf/document/optimize/
---
## Metodo Document.Optimize

Linearizza il documento per - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguire il link alla pagina successiva il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva quando i dati per una pagina vengono consegnati su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un link, anche prima che l'intera pagina sia stata ricevuta e visualizzata. Invocare questo metodo non salva effettivamente il documento. Al contrario, il documento è solo preparato per avere una struttura ottimizzata, quindi chiama Salva per ottenere il documento ottimizzato.

```csharp
public void Optimize()
```

### Esempi

Il seguente esempio mostra come ottimizzare un documento PDF per il web.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)