---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Método TextFragmentAbsorber. Realiza una búsqueda en la página especificada
type: docs
weight: 150
url: /es/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Realiza una búsqueda en la página especificada.

```csharp
public override void Visit(Page page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | Objeto de página del documento PDF. |

## Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Realiza una búsqueda en el documento especificado.

```csharp
public override void Visit(Document pdf)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdf | Document | Objeto del documento PDF. |

## Ejemplos

El ejemplo demuestra cómo encontrar texto en el documento PDF y reemplazar el texto de todas las ocurrencias de búsqueda.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Realiza una búsqueda en el objeto de formulario especificado.

```csharp
public void Visit(XForm xForm)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xForm | XForm | Objeto de formulario PDF. |

### Ver También

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)