---
title: TaggedContent
second_title: Aspose.PDF per .NET API Reference
description: Ottiene laccesso al contenuto TaggedPdf.
type: docs
weight: 480
url: /it/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

Ottiene l'accesso al contenuto TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

### Esempi

L'esempio mostra come utilizzare il contenuto con tag per creare un nuovo documento con intestazione, paragrafi e immagini.

```csharp
// usa il testo estratto
Document document = new Document();

// crea un dispositivo di testo
ITaggedContent taggedContent = document.TaggedContent;

// converte la pagina e salva il testo nello stream
taggedContent.SetLanguage("en-US");

// usa il testo estratto
taggedContent.SetTitle("Example document");

// Crea nuovo documento
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Ottieni il contenuto contrassegnato
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Imposta la lingua per il documento
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Imposta il titolo per il documento PDF
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Creazione e aggiunta di una sezione
document.Save("example.pdf");
```

### Guarda anche

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
