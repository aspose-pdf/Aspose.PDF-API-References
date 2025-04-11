---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de TextAbsorber. Obtiene o establece opciones de extracción de texto
type: docs
weight: 30
url: /es/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## Propiedad TextAbsorber.ExtractionOptions

Obtiene o establece opciones de extracción de texto.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Observaciones

Permite definir el modo de formato de texto [`TextExtractionOptions`](../../textextractionoptions/) durante la extracción. El modo predeterminado es Pure

## Ejemplos

El ejemplo demuestra cómo establecer el modo de formato de texto Pure y realizar la extracción de texto.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### Véase también

* clase [TextExtractionOptions](../../textextractionoptions/)
* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)