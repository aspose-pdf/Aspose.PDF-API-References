---
title: "PdfXmpMetadata.Contains"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 메서드. 사전에 지정된 키가 포함되어 있는지 확인합니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

사전에 지정된 키가 포함되어 있는지 확인합니다.

```csharp
public bool Contains(string key)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | String | 확인할 키. |

### 반환 값

사전에 지정된 키가 포함되어 있으면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

사전에 지정된 속성이 포함되어 있는지 확인합니다.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | DefaultMetadataProperties | 확인할 속성. |

### 반환 값

사전에 지정된 속성이 포함되어 있으면 True, 그렇지 않으면 false.

### 또 보기

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

지정된 키-값 쌍이 사전에 포함되어 있는지 확인합니다.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | KeyValuePair`2 | 키-값 쌍. |

### 반환 값

이 쌍이 발견되면 true.

### 또 보기

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


