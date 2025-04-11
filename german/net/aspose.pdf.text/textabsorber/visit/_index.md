---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber-Methode. Extrahiert Text auf der angegebenen Seite
type: docs
weight: 70
url: /de/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrahiert Text auf der angegebenen Seite

```csharp
public virtual void Visit(Page page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Page | Pdf-Dokumentseitenobjekt. |

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extrahiert Text auf dem angegebenen XForm.

```csharp
public virtual void Visit(XForm form)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| form | XForm | Pdf-Formularobjekt. |

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [XForm](../../../aspose.pdf/xform/)
* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrahiert Text auf dem angegebenen Dokument

```csharp
public virtual void Visit(Document pdf)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdf | Document | Pdf-Dokumentobjekt. |

## Beispiele

Das Beispiel zeigt, wie man Text im PDF-Dokument extrahiert.

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

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)