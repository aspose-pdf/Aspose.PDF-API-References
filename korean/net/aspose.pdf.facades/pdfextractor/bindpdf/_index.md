---
title: "PdfExtractor.BindPdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfExtractor 메서드. 입력 PDF 파일을 바인드합니다."
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
| inputFile | String | 바인드할 PDF 파일 |

## 예제

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

스트림에서 PDF 문서를 바인딩합니다.

```csharp
public override void BindPdf(Stream inputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | PDF 문서 데이터를 포함하는 스트림 |

## 예제

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


