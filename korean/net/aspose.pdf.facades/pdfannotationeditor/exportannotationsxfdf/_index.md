---
title: "PdfAnnotationEditor.ExportAnnotationsXfdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAnnotationEditor 메서드. 지정된 주석 유형의 내용을 XFDF로 내보냅니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

지정된 주석 유형의 내용을 XFDF로 내보냅니다.

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xmlOutputStream | Stream | 출력 XFDF 스트림입니다. |
| start | Int32 | 문서의 주석이 내보내질 시작 페이지입니다. |
| end | Int32 | 문서의 주석이 내보내질 종료 페이지입니다. |
| annotTypes | String[] | 내보낼 주석 유형의 배열입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### 또 보기

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

지정된 주석 유형의 내용을 XFDF로 내보냅니다.

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xmlOutputStream | Stream | 출력 XFDF 스트림입니다. |
| start | Int32 | 문서의 주석이 내보내질 시작 페이지입니다. |
| end | Int32 | 문서의 주석이 내보내질 종료 페이지입니다. |
| annotTypes | AnnotationType[] | 내보낼 주석 유형의 배열입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### 또 보기

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


