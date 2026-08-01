---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 지정된 ID를 가진 스탬프를 문서의 모든 페이지에서 삭제합니다."
type: docs
weight: 350
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

문서의 모든 페이지에서 지정된 ID를 가진 스탬프를 삭제합니다.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stampIds | Int32[] | 스탬프 ID 배열. |

## 예제

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

지정된 페이지에서 여러 스탬프 ID로 스탬프를 삭제합니다.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 스탬프가 삭제될 페이지 번호. |
| stampIds | Int32[] | 스탬프 ID 배열. |

## 예제

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


