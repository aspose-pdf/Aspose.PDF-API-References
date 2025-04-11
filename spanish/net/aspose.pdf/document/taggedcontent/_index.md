---
title: Document.TaggedContent
second_title: Aspose.PDF for .NET API Reference
description: Propiedad del documento. Obtiene acceso al contenido TaggedPdf
type: docs
weight: 520
url: /es/net/aspose.pdf/document/taggedcontent/
---
## Propiedad Document.TaggedContent

Obtiene acceso al contenido TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Ejemplos

El ejemplo demuestra cómo usar contenido etiquetado para crear un nuevo documento con encabezado, párrafos e imágenes.

```csharp
// Create new document
Document document = new Document();

// Get the tagged content
ITaggedContent taggedContent = document.TaggedContent;

// Set language for document
taggedContent.SetLanguage("en-US");

// Set title for PDF document
taggedContent.SetTitle("Example document");

// Creating and adding Section
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Create Header
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Create paragraph
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Create illustration
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Save document
document.Save("example.pdf");
```

### Véase también

* interfaz [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)