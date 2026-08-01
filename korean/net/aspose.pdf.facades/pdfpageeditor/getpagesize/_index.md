---
title: "PdfPageEditor.GetPageSize"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfPageEditor method. 지정된 페이지의 페이지 크기를 반환합니다"
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

지정된 페이지의 페이지 크기를 반환합니다.

```csharp
public PageSize GetPageSize(int page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | Int32 | 페이지 인덱스. 문서 페이지는 1부터 번호가 매겨집니다. |

### 반환 값

결과는 PageSize 인스턴스입니다. 반환된 객체의 Width 및 Height 속성을 사용하여 페이지 너비와 높이를 가져옵니다.

## 예제

다음 예제는 GetPageSize 메서드 사용을 보여줍니다:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


