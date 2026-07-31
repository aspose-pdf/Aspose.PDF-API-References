---
title: "Document.TaggedContent"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Document. Ottiene l'accesso al contenuto TaggedPdf"
type: docs
weight: 540
url: /it/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

Ottiene l'accesso al contenuto TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Esempi

L'esempio dimostra come utilizzare il contenuto taggato per creare un nuovo documento con intestazione, paragrafi e immagini.

```csharp
// Crea nuovo documento
Document document = new Document();

// Ottieni il contenuto taggato
ITaggedContent taggedContent = document.TaggedContent;

// Imposta la lingua per il documento
taggedContent.SetLanguage("en-US");

// Imposta il titolo per il documento PDF
taggedContent.SetTitle("Example document");

// Creazione e aggiunta della Sezione
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Crea Header
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Crea paragrafo
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Crea illustrazione
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Salva documento
document.Save("example.pdf");
```

### Vedi anche

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


