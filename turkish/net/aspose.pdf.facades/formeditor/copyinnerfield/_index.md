---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar. Kaynak belgenin sahip olduğu her şeyi içeren yeni bir belge üretilecektir, yeni kopyalanan alan hariç.
type: docs
weight: 150
url: /tr/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar. Kaynak belgenin sahip olduğu her şeyi içeren yeni bir belge üretilecektir, yeni kopyalanan alan hariç.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Eski tam nitelikli alan adı. |
| newFieldName | String | Yeni tam nitelikli alan adı. Null ise, fieldName + "~" olarak ayarlanacaktır. |
| pageNum | Int32 | Yeni alanı tutacak sayfa numarası. -1 ise, yeni alan eski alanın bulunduğu aynı sayfaya kopyalanacaktır. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Ayrıca Bakınız

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Mevcut bir alanı hem sayfa numarası hem de ordinatlarla belirtilen yeni bir konuma kopyalar. Kaynak belgenin sahip olduğu her şeyi içeren yeni bir belge üretilecektir, yeni kopyalanan alan hariç.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Eski tam nitelikli alan adı. |
| newFieldName | String | Yeni tam nitelikli alan adı. Null ise, fieldName + "~" olarak ayarlanacaktır. |
| pageNum | Int32 | Yeni alanı tutacak sayfa numarası. -1 ise, yeni alan eski alanın bulunduğu aynı sayfaya kopyalanacaktır. |
| abscissa | Single | Yeni alanın abscissası. -1 ise, abscissa orijinal olanla eşitlenecektir. |
| ordinate | Single | Yeni alanın ordinatı. -1 ise, ordinat orijinal olanla eşitlenecektir. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Ayrıca Bakınız

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)