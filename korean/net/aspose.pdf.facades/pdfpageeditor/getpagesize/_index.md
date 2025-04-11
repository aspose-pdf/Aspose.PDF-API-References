---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 메서드. 지정된 페이지의 페이지 크기를 반환합니다.
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize 메서드

지정된 페이지의 페이지 크기를 반환합니다.

```csharp
public PageSize GetPageSize(int page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 페이지 인덱스. 문서 페이지는 1부터 번호가 매겨집니다. |

### 반환 값

결과는 PageSize의 인스턴스입니다. 반환된 객체의 Width 및 Height 속성을 사용하여 페이지 너비와 높이를 가져옵니다.

## 예제

다음 예제는 GetPageSize 메서드 사용을 보여줍니다:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfPageEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)