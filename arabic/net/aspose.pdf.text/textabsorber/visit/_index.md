---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextAbsorber. تستخرج النص من الصفحة المحددة
type: docs
weight: 70
url: /ar/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

تستخرج النص من الصفحة المحددة

```csharp
public virtual void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | كائن صفحة مستند PDF. |

## Examples

توضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF.

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

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

تستخرج النص من XForm المحدد.

```csharp
public virtual void Visit(XForm form)
```

| Parameter | Type | Description |
| --- | --- | --- |
| form | XForm | كائن نموذج PDF. |

## Examples

توضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF.

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

### See Also

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

تستخرج النص من المستند المحدد

```csharp
public virtual void Visit(Document pdf)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdf | Document | كائن مستند PDF. |

## Examples

توضح المثال كيفية استخراج النص من مستند PDF.

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

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)