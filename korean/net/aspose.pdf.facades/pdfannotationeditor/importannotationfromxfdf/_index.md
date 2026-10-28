---
title: "PdfAnnotationEditor.ImportAnnotationFromXfdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAnnotationEditor 메서드. XFDF 파일에서 지정된 주석을 가져옵니다."
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

XFDF 파일에서 지정된 주석을 가져옵니다.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xfdfFile | String | 입력 XFDF 파일입니다. |
| annotType | AnnotationType[] | 가져올 주석 배열입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### 또 보기

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

XFDF 데이터 스트림에서 지정된 주석을 가져옵니다.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xfdfStream | Stream | 입력 XFDF 데이터 스트림입니다. |
| annotType | AnnotationType[] | 가져올 주석 유형의 배열입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### 또 보기

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


