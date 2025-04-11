---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Método TextAbsorber. Extrae texto en la página especificada
type: docs
weight: 70
url: /es/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrae texto en la página especificada

```csharp
public virtual void Visit(Page page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | Objeto de página del documento Pdf. |

## Ejemplos

El ejemplo demuestra cómo extraer texto en la primera página del documento PDF.

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

### Ver También

* clase [Page](../../../aspose.pdf/page/)
* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extrae texto en el XForm especificado.

```csharp
public virtual void Visit(XForm form)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| form | XForm | Objeto de formulario Pdf. |

## Ejemplos

El ejemplo demuestra cómo extraer texto en la primera página del documento PDF.

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

### Ver También

* clase [XForm](../../../aspose.pdf/xform/)
* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrae texto en el documento especificado

```csharp
public virtual void Visit(Document pdf)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdf | Document | Objeto del documento Pdf. |

## Ejemplos

El ejemplo demuestra cómo extraer texto en el documento PDF.

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

### Ver También

* clase [Document](../../../aspose.pdf/document/)
* clase [TextAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)