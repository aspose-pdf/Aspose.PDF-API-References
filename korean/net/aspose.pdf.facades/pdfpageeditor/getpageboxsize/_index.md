---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfPageEditor 메서드. 문서에서 지정된 상자의 크기를 반환합니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

문서에서 지정된 상자의 크기를 반환합니다.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | Int32 | 페이지 인덱스. 문서 페이지는 1부터 번호가 매겨집니다. |
| pageBoxName | String | 상자 유형 이름. 유효한 값은: "art", "bleed", "crop", "media", "trim". |

### 반환 값

요청된 상자를 포함하는 사각형.

## 예제

다음 예제는 첫 번째 페이지의 media box를 가져오는 방법을 보여줍니다:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### 또 보기

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


