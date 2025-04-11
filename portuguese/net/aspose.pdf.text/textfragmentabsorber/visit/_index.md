---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Método TextFragmentAbsorber. Realiza busca na página especificada
type: docs
weight: 150
url: /pt/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Realiza busca na página especificada.

```csharp
public override void Visit(Page page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | Objeto de página do documento PDF. |

## Exemplos

O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.

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

### Veja Também

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Realiza busca no documento especificado.

```csharp
public override void Visit(Document pdf)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdf | Document | Objeto do documento PDF. |

## Exemplos

O exemplo demonstra como encontrar texto no documento PDF e substituir o texto de todas as ocorrências da busca.

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

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Realiza busca no objeto de formulário especificado.

```csharp
public void Visit(XForm xForm)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xForm | XForm | Objeto de formulário PDF. |

### Veja Também

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)