---
title: Text
second_title: Aspose.PDF per .NET API Reference
description: Ottiene il testo estratto che ilTextAbsorberaspose.pdf.text/textabsorber estratti nel documento o nella pagina PDF.
type: docs
weight: 50
url: /it/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

Ottiene il testo estratto che il[`TextAbsorber`](../../textabsorber) estratti nel documento o nella pagina PDF.

```csharp
public virtual string Text { get; }
```

### Esempi

L'esempio mostra come estrarre il testo da tutte le pagine del documento PDF.

```csharp
// apri il documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre il testo
TextAbsorber absorber = new TextAbsorber();

// accetta l'assorbitore per la prima pagina
doc.Pages.Accept(absorber);

// ottieni il testo estratto
string extractedText = absorber.Text;

```

### Guarda anche

* class [TextAbsorber](../../textabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textabsorber)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
