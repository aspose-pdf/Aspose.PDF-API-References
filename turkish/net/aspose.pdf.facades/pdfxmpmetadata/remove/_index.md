---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metodu. Belirtilen anahtara sahip öğeyi kaldırır
type: docs
weight: 210
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Belirtilen anahtara sahip öğeyi kaldırır.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | DefaultMetadataProperties | Silinecek öğenin anahtarı. |

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Ayrıca Bakınız

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Sözlükten anahtarı kaldırır.

```csharp
public bool Remove(string key)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | String | Kaldırılacak anahtar. |

### Dönüş Değeri

True - eğer anahtar kaldırıldıysa; aksi takdirde, false.

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Ayrıca Bakınız

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Koleksiyondan anahtar/değer çiftini kaldırır.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | KeyValuePair`2 | Kaldırılacak anahtar/değer çifti. |

### Dönüş Değeri

Eğer çift bulunduysa ve kaldırıldıysa true.

### Ayrıca Bakınız

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)