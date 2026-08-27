---
title: "TextAbsorber.Visit"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextAbsorber 메서드. 지정된 페이지에서 텍스트를 추출합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

지정된 페이지에서 텍스트를 추출합니다.

```csharp
public virtual void Visit(Page page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | 페이지 | Pdf 문서 페이지 객체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber();

// 문서의 모든 페이지에 대해 흡수기를 수락합니다.
absorber.Visit(doc.Pages[1]);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;
```

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 폼 | XForm | Pdf 양식 개체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber();

// 문서의 모든 페이지에 대해 흡수기를 수락합니다.
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;
```

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdf | Document | Pdf 문서 객체. |

## 예제

예제는 PDF 문서에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber();

// 문서의 모든 페이지에 대해 흡수기를 수락합니다.
absorber.Visit(doc);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;
```

### 또 보기

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


