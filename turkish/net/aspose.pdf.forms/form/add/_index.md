---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. Formda alan ekler
type: docs
weight: 190
url: /tr/net/aspose.pdf.forms/form/add/
---
## Ekle(Field, int) {#add_2}

Formda alan ekler.

```csharp
public void Add(Field field, int pageNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| field | Field | Eklenmesi gereken alan. |
| pageNumber | Int32 | Eklenen alanın yerleştirileceği sayfa indeksi. |

### Ayrıca Bakınız

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Ekle(Field) {#add_1}

Formda alan ekler.

```csharp
public void Add(Field field)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| field | Field | Eklenmesi gereken alan. |

### Ayrıca Bakınız

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Ekle(Field, string, int) {#add}

Formda yeni bir alan ekler; Eğer bu alan başka bir formda veya bu formda zaten yer alıyorsa, alanın bir kopyası oluşturulur.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| field | Field | Alan adı. |
| partialName | String | Formdaki alanın adı. |
| pageNumber | Int32 | Alanın ekleneceği sayfa numarası. |

### Dönüş Değeri

Eklenen alan döndürülür. Eğer alanın bir kopyası oluşturulduysa, o da döndürülür.

### Ayrıca Bakınız

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)