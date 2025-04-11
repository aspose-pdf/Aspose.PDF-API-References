---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: Propiedad TextFragment. Obtiene o establece el objeto de texto String que representa el objeto TextFragment
type: docs
weight: 130
url: /es/net/aspose.pdf.text/textfragment/text/
---
## Propiedad TextFragment.Text

Obtiene o establece el objeto de texto String que representa el [`TextFragment`](../) objeto.

```csharp
public string Text { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo buscar un texto y reemplazar la primera ocurrencia representada con el objeto [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ver También

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [Document](../../../aspose.pdf/document/)
* clase [TextFragment](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)