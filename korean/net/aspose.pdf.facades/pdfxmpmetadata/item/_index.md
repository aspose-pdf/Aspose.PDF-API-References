---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 속성. 키로 값을 가져오거나 설정합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata 인덱서 (1 중 2)

키로 값을 가져오거나 설정합니다.

```csharp
public XmpValue this[string key] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| key | 가져오거나 설정할 키 이름입니다. |

### 반환 값

키에 따른 객체

## 예제

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### 참조

* 클래스 [XmpValue](../../../aspose.pdf/xmpvalue/)
* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## PdfXmpMetadata 인덱서 (2 중 2)

키로 XMP 메타데이터의 값을 가져옵니다.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| key | 값의 키입니다. |

### 반환 값

XMP 메타데이터에서 가져온 값입니다.

## 예제

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### 참조

* 클래스 [XmpValue](../../../aspose.pdf/xmpvalue/)
* 열거형 [DefaultMetadataProperties](../../defaultmetadataproperties/)
* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)