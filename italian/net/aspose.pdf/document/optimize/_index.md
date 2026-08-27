---
title: "Document.Optimize"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Document metodo. Linearizza il documento in modo da  aprire la prima pagina il più rapidamente possibile  visualizzare la pagina successiva o seguire il collegamento alla pagina successiva il più rapidamente possibile  visualizzare la pagina in modo incrementale man mano che arriva quando i dati per una pagina sono trasmessi su un canale lento, visualizzare prima i dati più utili  consentire l'interazione dell'utente, ad esempio seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata. L'invocazione di questo metodo non salva effettivamente il documento. Al contrario, il documento viene solo preparato con una struttura ottimizzata; chiamare quindi Save per ottenere il documento ottimizzato"
type: docs
weight: 770
url: /it/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

Linearizzare il documento per - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguire il collegamento alla pagina successiva il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva quando i dati per una pagina vengono consegnati su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata. L'invocazione di questo metodo non salva effettivamente il documento. Al contrario, il documento viene solo preparato per avere una struttura ottimizzata; chiamare quindi Save per ottenere il documento ottimizzato.

```csharp
public void Optimize()
```

### Esempi

Il seguente esempio mostra come ottimizzare un documento PDF per il web.

```csharp
[C#]
	// Il percorso al tuo file PDF.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Apri documento
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Ottimizza per il web
	pdfDocument.Optimize();

	// Salva documento di output
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

### Vedi anche

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


