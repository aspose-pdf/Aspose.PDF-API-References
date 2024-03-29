---
title: Phrase
second_title: Referencia de API de Aspose.PDF para .NET
description: Obtiene o establece la frase que elTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber búsquedas en el documento o página PDF.
type: docs
weight: 50
url: /es/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Obtiene o establece la frase que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas en el documento o página PDF.

```csharp
public string Phrase { get; set; }
```

### Ejemplos

El ejemplo demuestra cómo realizar búsquedas de texto varias veces y realizar reemplazos de texto.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// busca otra palabra y la reemplaza
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
