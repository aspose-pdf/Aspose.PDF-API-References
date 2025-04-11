---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Método TextAbsorber. Extrai texto na página especificada
type: docs
weight: 70
url: /pt/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrai texto na página especificada

```csharp
public virtual void Visit(Page page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | Objeto de página do documento Pdf. |

## Exemplos

O exemplo demonstra como extrair texto na primeira página do documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extrai texto no XForm especificado.

```csharp
public virtual void Visit(XForm form)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| form | XForm | Objeto de formulário Pdf. |

## Exemplos

O exemplo demonstra como extrair texto na primeira página do documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### Veja Também

* classe [XForm](../../../aspose.pdf/xform/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrai texto no documento especificado

```csharp
public virtual void Visit(Document pdf)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdf | Document | Objeto do documento Pdf. |

## Exemplos

O exemplo demonstra como extrair texto no documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### Veja Também

* classe [Document](../../../aspose.pdf/document/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)