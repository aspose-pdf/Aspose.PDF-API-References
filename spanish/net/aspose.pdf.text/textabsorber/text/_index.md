---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de TextAbsorber. Obtiene el texto extraído que el TextAbsorber extrae del documento o página PDF
type: docs
weight: 50
url: /es/net/aspose.pdf.text/textabsorber/text/
---
## Propiedad TextAbsorber.Text

Obtiene el texto extraído que el [`TextAbsorber`](../) extrae del documento o página PDF.

```csharp
public virtual string Text { get; }
```

## Ejemplos

El ejemplo demuestra cómo extraer texto de todas las páginas del documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Véase también

* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)