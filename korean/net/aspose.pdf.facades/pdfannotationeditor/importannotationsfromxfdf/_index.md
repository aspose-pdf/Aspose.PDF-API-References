---
title: "PdfAnnotationEditor.ImportAnnotationsFromXfdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAnnotationEditor 메서드. XFDF 파일에서 모든 주석을 가져옵니다."
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

XFDF 파일에서 모든 주석을 가져옵니다.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xfdfFile | String | 입력 XFDF 파일입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

XFDF 데이터 스트림에서 모든 주석을 가져옵니다.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xfdfStream | Stream | 입력 XFDF 데이터 스트림입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


