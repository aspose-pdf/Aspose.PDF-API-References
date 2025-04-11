---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 메서드. 지정된 키로 요소를 제거합니다.
type: docs
weight: 210
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

지정된 키로 요소를 제거합니다.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | 삭제될 요소의 키입니다. |

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | 제거될 키입니다. |

### Return Value

True - 키가 제거되면; 그렇지 않으면 false입니다.

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

컬렉션에서 키/값 쌍을 제거합니다.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | 제거될 키/값 쌍입니다. |

### Return Value

쌍이 발견되어 제거되면 true입니다.

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)