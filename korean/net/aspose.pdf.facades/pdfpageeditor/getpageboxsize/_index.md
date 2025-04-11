---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 메서드. 문서에서 지정된 박스의 크기를 반환합니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize 메서드

문서에서 지정된 박스의 크기를 반환합니다.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 페이지 인덱스. 문서 페이지는 1부터 번호가 매겨집니다. |
| pageBoxName | String | 박스 유형 이름. 유효한 값은: "art", "bleed", "crop", "media", "trim"입니다. |

### 반환 값

요청된 박스를 포함하는 사각형입니다.

## 예제

다음 예제는 첫 번째 페이지의 미디어 박스를 가져오는 방법을 보여줍니다:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### 참조

* 클래스 [PdfPageEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)