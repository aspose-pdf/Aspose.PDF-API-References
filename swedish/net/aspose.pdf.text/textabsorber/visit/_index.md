---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber metod. Extraherar text på den angivna sidan
type: docs
weight: 70
url: /sv/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Extraherar text på den angivna sidan

```csharp
public virtual void Visit(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Pdf dokument sidobjekt. |

## Exempel

Exemplet visar hur man extraherar text på den första PDF-dokument sidan.

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

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extraherar text på den angivna XForm.

```csharp
public virtual void Visit(XForm form)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| form | XForm | Pdf formulärobjekt. |

## Exempel

Exemplet visar hur man extraherar text på den första PDF-dokument sidan.

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

### Se Även

* klass [XForm](../../../aspose.pdf/xform/)
* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extraherar text på det angivna dokumentet

```csharp
public virtual void Visit(Document pdf)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdf | Document | Pdf dokumentobjekt. |

## Exempel

Exemplet visar hur man extraherar text på PDF-dokumentet.

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

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)