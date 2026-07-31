---
title: "TextBuilder.AppendParagraph"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TextBuilder. Aggiunge un paragrafo di testo alla pagina Pdf"
type: docs
weight: 20
url: /it/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

Aggiunge un paragrafo di testo alla pagina Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textParagraph | TextParagraph | Oggetto paragrafo di testo. |

## Esempi

L'esempio dimostra come creare un oggetto TextParagraph e aggiungerlo alla pagina Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// crea TextParagraph
TextParagraph paragraph = new TextParagraph();
           
// imposta il rettangolo del paragrafo
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// imposta le opzioni di a capo automatico
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// aggiungi righe di stringa
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// aggiungi il paragrafo alla pagina Pdf con il TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// salva il documento Pdf
doc.Save(outFile);
```

### Vedi anche

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


