---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. PDF 문서에서 사용자 정의 작업에 대한 링크를 생성합니다.
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink 메서드

PDF 문서에서 사용자 정의 작업에 대한 링크를 생성합니다.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| originalPage | Int32 | 링크와 함께 사각형이 생성될 원본 페이지의 번호입니다. |
| color | Color | 활성 클릭을 위한 사각형의 색상입니다. |
| actionName | Enum[] | Acrobat 뷰어에서 메뉴 항목을 실행하는 데 해당하는 작업(PredefinedAction 열거형의 구성원) 배열입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)