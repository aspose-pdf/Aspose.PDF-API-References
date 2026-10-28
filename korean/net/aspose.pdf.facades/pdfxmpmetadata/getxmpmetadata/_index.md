---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 메서드. 입력 PDF의 XmpMetadata를 XML 형식으로 가져옵니다."
type: docs
weight: 190
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

입력 PDF의 XmpMetadata를 XML 형식으로 가져옵니다.

```csharp
public byte[] GetXmpMetadata()
```

### 반환 값

XmpMetadata의 바이트.

## 예제

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

입력 PDF의 XmpMetadata 중 메타 이름에 따라 일부를 가져옵니다.

```csharp
public byte[] GetXmpMetadata(string name)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | String | 메타데이터 이름. |

### 반환 값

메타데이터의 바이트.

## 예제

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


