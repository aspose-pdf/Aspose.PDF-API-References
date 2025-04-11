---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 파일 첨부 주석을 생성합니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

파일 첨부 주석을 생성합니다.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| filePath | String | 첨부될 파일의 경로입니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| name | String | 주석을 표시하는 데 사용될 아이콘의 이름입니다. 이 값은 "Graph", "PushPin", "Paperclip", "Tag"일 수 있습니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### 참조

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

파일 첨부 주석을 생성합니다.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| filePath | String | 첨부될 파일의 경로입니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| name | String | 주석을 표시하는 데 사용될 아이콘의 이름입니다. 이 값은 "Graph", "PushPin", "Paperclip", "Tag"일 수 있습니다. |
| opacity | Double | 아이콘의 불투명도: 0에서 1까지, 0 - 완전히 투명, 1 - 완전히 불투명. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### 참조

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

파일 첨부 주석을 생성합니다.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| attachmentStream | Stream | 첨부 파일 스트림입니다. |
| attachmentName | String | 첨부 이름입니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| name | String | 주석을 표시하는 데 사용될 아이콘의 이름입니다. 이 값은 "Graph", "PushPin", "Paperclip", "Tag"일 수 있습니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### 참조

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

파일 첨부 주석을 생성합니다.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| attachmentStream | Stream | 첨부 파일 스트림입니다. |
| attachmentName | String | 첨부 이름입니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| name | String | 주석을 표시하는 데 사용될 아이콘의 이름입니다. 이 값은 "Graph", "PushPin", "Paperclip", "Tag"일 수 있습니다. |
| opacity | Double | 아이콘의 불투명도: 0에서 1까지, 0 - 완전히 투명, 1 - 완전히 불투명. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### 참조

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)