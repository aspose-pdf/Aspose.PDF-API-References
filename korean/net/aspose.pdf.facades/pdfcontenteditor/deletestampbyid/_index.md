---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 지정된 페이지에서 스탬프 ID로 스탬프를 삭제합니다.
type: docs
weight: 340
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

지정된 페이지에서 스탬프 ID로 스탬프를 삭제합니다.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 스탬프가 삭제될 페이지 번호입니다. |
| stampId | Int32 | 삭제해야 할 스탬프의 식별자입니다. |

## 예제

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

문서의 모든 페이지에서 ID로 스탬프를 삭제합니다.

```csharp
public void DeleteStampById(int stampId)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stampId | Int32 | 삭제해야 할 스탬프의 식별자입니다. |

## 예제

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)