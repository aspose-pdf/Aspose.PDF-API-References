---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: 스탬프 메서드. 스탬프로 사용될 PDF 파일과 페이지 번호를 설정합니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

스탬프로 사용될 PDF 파일과 페이지 번호를 설정합니다.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfFile | String | PDF 파일의 경로. |
| pageNumber | Int32 | PDF 파일의 페이지 번호 |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 참조

* 클래스 [Stamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

스탬프로 사용될 PDF 파일과 페이지 번호를 설정합니다.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfStream | Stream | PDF 문서를 포함하는 스트림. |
| pageNumber | Int32 | 스탬프로 사용될 문서의 페이지 인덱스. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 참조

* 클래스 [Stamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)