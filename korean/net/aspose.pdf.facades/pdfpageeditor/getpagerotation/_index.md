---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 메서드. 지정된 페이지의 회전을 반환합니다.
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation 메서드

지정된 페이지의 회전을 반환합니다.

```csharp
public int GetPageRotation(int page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 페이지 인덱스. 문서 페이지는 1부터 번호가 매겨집니다. |

### 반환 값

도 단위의 페이지 회전.

## 예제

다음 예제는 페이지 회전을 가져오는 방법을 보여줍니다:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### 참조

* 클래스 [PdfPageEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)