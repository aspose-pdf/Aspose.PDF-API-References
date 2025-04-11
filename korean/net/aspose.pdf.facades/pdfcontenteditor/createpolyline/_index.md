---
title: PdfContentEditor.CreatePolyLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 폴리라인 주석을 생성합니다.
type: docs
weight: 240
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## PdfContentEditor.CreatePolyLine 메서드

폴리라인 주석을 생성합니다.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lineInfo | LineInfo | LineInfo 클래스의 인스턴스입니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| annotRect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| annotContents | String | 주석의 내용입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [LineInfo](../../lineinfo/)
* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)