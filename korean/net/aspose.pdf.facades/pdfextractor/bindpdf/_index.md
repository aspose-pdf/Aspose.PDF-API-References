---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 메서드. 입력 PDF 파일 바인딩
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

입력 PDF 파일을 바인딩합니다.

```csharp
public override void BindPdf(string inputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 바인딩할 PDF 파일 |

## 예제

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### 참조

* 클래스 [PdfExtractor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

스트림에서 PDF 문서를 바인딩합니다.

```csharp
public override void BindPdf(Stream inputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | PDF 문서 데이터가 포함된 스트림 |

## 예제

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### 참조

* 클래스 [PdfExtractor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)