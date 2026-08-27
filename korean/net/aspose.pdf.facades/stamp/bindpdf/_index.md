---
title: "Stamp.BindPdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Stamp 메서드. 스탬프로 사용할 PDF 파일과 페이지 번호를 설정합니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

스탬프로 사용할 PDF 파일과 페이지 번호를 설정합니다.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfFile | String | PDF 파일 경로입니다. |
| pageNumber | Int32 | PDF 파일의 페이지 번호 |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//첫 번째 페이지가 스탬프로 사용됩니다.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 또 보기

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

스탬프로 사용할 PDF 파일과 페이지 번호를 설정합니다.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfStream | Stream | PDF 문서를 포함하는 스트림입니다. |
| pageNumber | Int32 | 스탬프로 사용될 문서의 페이지 인덱스입니다. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//첫 번째 페이지가 스탬프로 사용됩니다.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 또 보기

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


