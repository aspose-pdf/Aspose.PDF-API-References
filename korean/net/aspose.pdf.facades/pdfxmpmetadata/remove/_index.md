---
title: "PdfXmpMetadata.Remove"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 메서드. 지정된 키를 가진 요소를 제거합니다."
type: docs
weight: 210
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

지정된 키를 가진 요소를 제거합니다.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | DefaultMetadataProperties | 삭제될 요소의 키. |

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### 또 보기

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

사전에서 키를 제거합니다.

```csharp
public bool Remove(string key)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | String | 제거될 키. |

### 반환 값

키가 제거되면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

컬렉션에서 키/값 쌍을 제거합니다.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | KeyValuePair`2 | 제거될 키/값 쌍. |

### 반환 값

쌍이 발견되어 제거되면 true.

### 또 보기

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


