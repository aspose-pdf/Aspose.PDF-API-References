---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 메서드. 지정된 페이지에서 텍스트를 추출합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

지정된 페이지에서 텍스트를 추출합니다.

```csharp
public virtual void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | Pdf 문서 페이지 객체. |

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

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

지정된 XForm에서 텍스트를 추출합니다.

```csharp
public virtual void Visit(XForm form)
```

| Parameter | Type | Description |
| --- | --- | --- |
| form | XForm | Pdf 양식 객체. |

## Examples

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

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

지정된 문서에서 텍스트를 추출합니다.

```csharp
public virtual void Visit(Document pdf)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdf | Document | Pdf 문서 객체. |

## Examples

이 예제는 PDF 문서에서 텍스트를 추출하는 방법을 보여줍니다.

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