---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 메서드. 사전이 지정된 키를 포함하는지 확인합니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

사전이 지정된 키를 포함하는지 확인합니다.

```csharp
public bool Contains(string key)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| key | String | 확인할 키입니다. |

### 반환 값

True - 사전에 지정된 키가 포함되어 있으면; 그렇지 않으면 false입니다.

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### 참조

* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

사전이 지정된 속성을 포함하는지 확인합니다.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| property | DefaultMetadataProperties | 확인할 속성입니다. |

### 반환 값

True - 사전에 지정된 속성이 포함되어 있으면; 그렇지 않으면 false입니다.

### 참조

* 열거형 [DefaultMetadataProperties](../../defaultmetadataproperties/)
* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

지정된 키-값 쌍이 사전에 포함되어 있는지 확인합니다.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | KeyValuePair`2 | 키-값 쌍입니다. |

### 반환 값

이 쌍이 발견되면 true입니다.

### 참조

* 클래스 [XmpValue](../../../aspose.pdf/xmpvalue/)
* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)