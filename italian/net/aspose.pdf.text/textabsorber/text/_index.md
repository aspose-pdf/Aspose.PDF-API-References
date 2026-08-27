---
title: "TextAbsorber.Text"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextAbsorber. Ottiene il testo estratto che il TextAbsorber estrae dal documento PDF o dalla pagina."
type: docs
weight: 50
url: /it/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

Ottiene il testo estratto che il [`TextAbsorber`](../) estrae dal documento PDF o dalla pagina.

```csharp
public virtual string Text { get; }
```

## Esempi

L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre testo
TextAbsorber absorber = new TextAbsorber();

// accetta l'assorbitore per tutte le pagine del documento
doc.Pages.Accept(absorber);

// ottieni il testo estratto
string extractedText = absorber.Text;

```

### Vedi anche

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


