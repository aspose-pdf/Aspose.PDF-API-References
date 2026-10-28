---
title: "PdfContentEditor.CreateWebLink"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서에 웹 링크를 생성합니다."
type: docs
weight: 300
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

PDF 문서에 웹 링크를 생성합니다.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| url | String | 웹 링크 대상입니다. |
| originalPage | Int32 | 웹 링크와 연결된 사각형이 생성될 원본 페이지 번호입니다. |
| clr | Color | 활성 클릭을 위한 사각형의 색상입니다. |
| actionName | Enum[] | Acrobat 뷰어에서 메뉴 항목을 실행하는 데 해당하는 동작 배열 (PredefinedAction 열거형의 멤버). |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

PDF 문서에 웹 링크를 생성합니다.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| url | String | 웹 링크 대상입니다. |
| originalPage | Int32 | 웹 링크가 바인딩된 사각형이 생성될 원본 페이지 번호. |
| clr | Color | 활성 클릭을 위한 사각형의 색상입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

PDF 문서에 웹 링크를 생성합니다.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| url | String | 웹 링크 대상입니다. |
| originalPage | Int32 | 웹 링크가 바인딩된 사각형이 생성될 원본 페이지 번호. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


