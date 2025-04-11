---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Formun belirtilen alanı zaten içerip içermediğini kontrol et
type: docs
weight: 280
url: /tr/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Formun belirtilen alanı zaten içerip içermediğini kontrol et.

```csharp
public bool HasField(Field field)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| field | Field | Kontrol edilecek alan. |

### Dönüş Değeri

`true` eğer belirtilen alan adı Form'a eklenmişse; aksi takdirde, `false`.

### Ayrıca Bakınız

* sınıf [Field](../../field/)
* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Belirtilen adı taşıyan alanın zaten Form'a eklenip eklenmediğini belirler.

```csharp
public bool HasField(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) veya [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) alanın. |

### Dönüş Değeri

`true` eğer belirtilen alan adı Form'a eklenmişse; aksi takdirde, `false`.

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Belirtilen adı taşıyan alanın zaten Form'a eklenip eklenmediğini belirler, alanların çocuk hiyerarşisine bakma yeteneği ile.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) veya [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) alanın. |
| searchChildren | Boolean | `true` olarak ayarlandığında, istenen *fieldName* için form alanlarının tüm hiyerarşisi aranacaktır (bu durumda gerekli alanın [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) *fieldName* olarak geçilmelidir). |

### Dönüş Değeri

`true` eğer belirtilen alan adı Form'a eklenmişse; aksi takdirde, `false`.

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)