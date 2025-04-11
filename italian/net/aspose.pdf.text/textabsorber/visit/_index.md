---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Metodo TextAbsorber. Estrae testo nella pagina specificata
type: docs
weight: 70
url: /it/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Estrae testo nella pagina specificata

```csharp
public virtual void Visit(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | Oggetto pagina del documento Pdf. |

## Esempi

L'esempio dimostra come estrarre testo nella prima pagina del documento PDF.

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

### Vedi Anche

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Estrae testo nel XForm specificato.

```csharp
public virtual void Visit(XForm form)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| form | XForm | Oggetto modulo Pdf. |

## Esempi

L'esempio dimostra come estrarre testo nella prima pagina del documento PDF.

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

### Vedi Anche

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Estrae testo nel documento specificato

```csharp
public virtual void Visit(Document pdf)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | Document | Oggetto documento Pdf. |

## Esempi

L'esempio dimostra come estrarre testo nel documento PDF.

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

### Vedi Anche

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)