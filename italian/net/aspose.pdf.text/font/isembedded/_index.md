---
title: "Font.IsEmbedded"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Font. Ottiene o imposta un valore che indica se il carattere è incorporato. Font basato su IFont verrà automaticamente sottoposto a subset e incorporato"
type: docs
weight: 60
url: /it/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

Restituisce o imposta un valore che indica se il font è incorporato. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato.

```csharp
public bool IsEmbedded { get; set; }
```

## Esempi

Il seguente esempio dimostra come trovare un carattere, contrassegnarlo come incorporato, cercare testo nella pagina del documento e sostituire il carattere del testo.

```csharp
// Crea un font e contrassegnalo per l'incorporamento
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// cambia il carattere per la prima occorrenza di testo
absorber.TextFragments[1].TextState.Font = font;

// salva il Document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


