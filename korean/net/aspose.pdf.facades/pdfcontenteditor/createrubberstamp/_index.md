---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 고무 도장 주석을 생성합니다.
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

고무 도장 주석을 생성합니다.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| annotRect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| icon | String | 주석을 표시하는 데 사용할 아이콘입니다. 기본값: 'Draft'. |
| annotContents | String | 주석의 내용입니다. |
| color | Color | 주석의 색상입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

고무 도장 주석을 생성합니다.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| annotRect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| annotContents | String | 주석의 내용입니다. |
| color | Color | 주석의 색상입니다. |
| appearanceFile | String | 외관 파일의 경로입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

고무 도장 주석을 생성합니다.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| annotRect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| annotContents | String | 주석의 내용입니다. |
| color | Color | 주석의 색상입니다. |
| appearanceStream | Stream | 외관 파일의 스트림입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)