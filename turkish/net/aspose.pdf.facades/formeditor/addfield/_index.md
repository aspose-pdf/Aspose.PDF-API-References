---
title: AddField
second_title: Aspose.PDF for .NET API Referansı
description: Belirtilen türdeki alanı forma ekleyin.
type: docs
weight: 140
url: /tr/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Belirtilen türdeki alanı forma ekleyin.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldType | FieldType | Eklenmesi gereken alanın türü. |
| fieldName | String | Eklenmesi gereken alanın adı. |
| pageNum | Int32 | Yeni alanın yerleştirilmesi gereken sayfa numarası. |
| llx | Single | Alanın sol alt köşesindeki apsis. |
| lly | Single | Alanın sol alt köşesinin ordinatı. |
| urx | Single | Alanın sağ üst köşesindeki apsis. |
| ury | Single | Alanın sağ üst köşesinin ordinatı. |

### Geri dönüş değeri

alan başarıyla eklendiyse true .

### Örnekler

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### Ayrıca bakınız

* enum [FieldType](../../fieldtype)
* class [FormEditor](../../formeditor)
* ad alanı [Aspose.Pdf.Facades](../../formeditor)
* toplantı [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Belirtilen türdeki alanı forma ekleyin.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldType | FieldType | Eklenmesi gereken alanın türü. |
| fieldName | String | Eklenmesi gereken alanın adı. |
| initValue | String | Alanın başlangıç değeri. |
| pageNum | Int32 | Yeni alanın yerleştirilmesi gereken sayfa numarası. |
| llx | Single | Alanın sol alt köşesindeki apsis. |
| lly | Single | Alanın sol alt köşesinin ordinatı. |
| urx | Single | Alanın sağ üst köşesindeki apsis. |
| ury | Single | Alanın sağ üst köşesinin ordinatı. |

### Geri dönüş değeri

alan başarıyla eklendiyse true .

### Örnekler

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### Ayrıca bakınız

* enum [FieldType](../../fieldtype)
* class [FormEditor](../../formeditor)
* ad alanı [Aspose.Pdf.Facades](../../formeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->