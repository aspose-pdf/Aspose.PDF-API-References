---
title: Text
second_title: Referencia de API de Aspose.PDF para .NET
description: Obtiene o estableceString objeto de texto que elTextFragmentaspose.pdf.text/textfragment objeto representa.
type: docs
weight: 130
url: /es/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

Obtiene o estableceString objeto de texto que el[`TextFragment`](../../textfragment) objeto representa.

```csharp
public string Text { get; set; }
```

### Ejemplos

El ejemplo demuestra cómo buscar un texto y reemplazar la primera aparición representada con[`TextFragment`](../../textfragment) objeto .

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambiar la fuente de la primera aparición de texto
absorber.TextFragments[1].Text = "hi world";

// Guardar documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ver también

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* class [Document](../../../aspose.pdf/document)
* class [TextFragment](../../textfragment)
* espacio de nombres [Aspose.Pdf.Text](../../textfragment)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
