---
title: "PdfXmpMetadata.Add"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 메서드. XMP 메타데이터에 값을 추가합니다."
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

XmpMetadata에 값을 추가합니다.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | DefaultMetadataProperties | 키 이름. |
| 값 | XmpValue | 추가될 값. |

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### 또 보기

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

메타데이터에 확장 필드를 추가합니다.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | 추가할 PDF 확장 객체. |
| namespacePrefix | String | 스키마의 접두사. |
| namespaceUri | String | 스키마의 네임스페이스 URI입니다. |
| schemaDescription | String | 스키마의 선택적 설명입니다. |

### 또 보기

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

사전 객체에 새 요소를 추가합니다.

```csharp
public void Add(string key, XmpValue value)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | String | 새 요소의 키입니다. |
| 값 | XmpValue | 요소의 값입니다. |

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### 또 보기

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

사전 객체에 새 요소를 추가합니다.

```csharp
public void Add(string key, object value)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | String | 새 요소의 키입니다. |
| 값 | Object | 요소의 값입니다. |

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

키와 값을 쌍으로 사전에 추가합니다.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | KeyValuePair`2 | 추가될 항목입니다. |

### 또 보기

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


