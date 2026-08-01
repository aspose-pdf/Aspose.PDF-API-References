---
title: "PdfContentEditor.CreateRubberStamp"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 고무 스탬프 주석을 생성합니다"
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

고무 스탬프 주석을 생성합니다.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |
| annotRect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| icon | String | 주석을 표시하는 데 사용될 아이콘입니다. 기본값: 'Draft'. |
| annotContents | String | 주석의 내용. |
| color | Color | 주석의 색상. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

고무 스탬프 주석을 생성합니다.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |
| annotRect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| annotContents | String | 주석의 내용. |
| color | Color | 주석의 색상. |
| appearanceFile | String | appearance 파일의 경로. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

고무 스탬프 주석을 생성합니다.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |
| annotRect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| annotContents | String | 주석의 내용. |
| color | Color | 주석의 색상. |
| appearanceStream | Stream | appearance 파일의 스트림. |

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

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


