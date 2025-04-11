---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Mevcut bir alanı bir PDF belgesinden diğerine orijinal sayfa numarası ve ordinatlarla kopyalar. Not: Sadece radyo kutusu hariç AcroForm alanları için
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Mevcut bir alanı bir PDF belgesinden diğerine orijinal sayfa numarası ve ordinatlarla kopyalar. Not: Sadece radyo kutusu hariç AcroForm alanları için.

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcFileName | String | Kopyalanacak alanı içeren PDF belgesinin adı. |
| fieldName | String | Orijinal tam nitelikli alan adı. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Mevcut bir alanı bir PDF belgesinden diğerine belirtilen sayfa numarası ve orijinal ordinatlarla kopyalar. Not: Sadece radyo kutusu hariç AcroForm alanları için.

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcFileName | String | Kopyalanacak alanı içeren PDF belgesinin adı. |
| fieldName | String | Orijinal tam nitelikli alan adı. |
| pageNum | Int32 | Yeni alanı tutacak sayfa numarası. -1 ise, yeni alan eski alanın bulunduğu aynı sayfaya kopyalanacaktır. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Mevcut bir alanı bir PDF belgesinden diğerine belirtilen sayfa numarası ve ordinatlarla kopyalar. Not: Sadece radyo kutusu hariç AcroForm alanları için.

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcFileName | String | Kopyalanacak alanı içeren PDF belgesinin adı. |
| fieldName | String | Orijinal tam nitelikli alan adı. |
| pageNum | Int32 | Yeni alanı tutacak sayfa numarası. -1 ise, yeni alan eski alanın bulunduğu aynı sayfaya kopyalanacaktır. |
| abscissa | Single | Yeni alanın abscissası. -1 ise, abscissa orijinal olanla eşit olacaktır. |
| ordinate | Single | Yeni alanın ordinatı. -1 ise, ordinat orijinal olanla eşit olacaktır. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)