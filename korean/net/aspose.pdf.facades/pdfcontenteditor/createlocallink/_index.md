---
title: PdfContentEditor.CreateLocalLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. PDF 문서에 로컬 링크를 생성합니다.
type: docs
weight: 190
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

PDF 문서에 로컬 링크를 생성합니다.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| desPage | Int32 | 목적지 페이지입니다. |
| originalPage | Int32 | 로컬 링크와 연결된 사각형이 생성될 원본 페이지의 번호입니다. |
| clr | Color | 활성 클릭을 위한 사각형의 색상입니다. |
| actionName | Enum[] | Acrobat 뷰어에서 메뉴 항목을 실행하는 것과 관련된 동작 배열(PredefinedAction 열거형의 멤버)입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

PDF 문서에 로컬 링크를 생성합니다.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| desPage | Int32 | 목적지 페이지입니다. |
| originalPage | Int32 | 로컬 링크와 연결된 사각형이 생성될 원본 페이지의 번호입니다. |
| clr | Color | 활성 클릭을 위한 사각형의 색상입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

PDF 문서에 로컬 링크를 생성합니다.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| desPage | Int32 | 목적지 페이지입니다. |
| originalPage | Int32 | 로컬 링크와 연결된 사각형이 생성될 원본 페이지의 번호입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)