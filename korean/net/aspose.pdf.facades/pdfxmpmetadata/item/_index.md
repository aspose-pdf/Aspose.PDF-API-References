---
title: "PdfXmpMetadata.Item"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 속성. 키로 값을 가져오거나 설정합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

키로 값을 가져오거나 설정합니다.

```csharp
public XmpValue this[string key] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| 키 | 가져오거나 설정할 키 이름. |

### 반환 값

키별 객체

## 예제

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### 또 보기

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

키를 사용하여 XMP 메타데이터 값을 가져옵니다.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| 키 | 값의 키. |

### 반환 값

XMP 메타데이터에서 가져온 값.

## 예제

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### 또 보기

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


