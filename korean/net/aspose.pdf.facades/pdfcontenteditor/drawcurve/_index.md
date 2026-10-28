---
title: "PdfContentEditor.DrawCurve"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 곡선 주석을 생성합니다"
type: docs
weight: 360
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve method

곡선 주석을 생성합니다.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lineInfo | LineInfo | LineInfo 클래스의 인스턴스. |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |
| annotRect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| annotContents | String | 주석의 내용. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### 또 보기

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


