---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Alanı tam nitelikli alan adına göre geçerli bir değerle doldurur. Alanları doldurmadan önce, her alanın adları ve karşılık gelen geçerli değerleri bilinmelidir. Hem alan adları hem de değerler büyük/küçük harf duyarlıdır. Lütfen Aspose.Pdf.Facades'ın yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit ile karşılaştırıldığında kısmi alan adlarıyla çalışmadığını unutmayın. Örneğin, alanın tam adı "Form.Subform.TextField" ise, tam adı belirtmelisiniz ve "TextField" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz.
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Belirtilen değerle alanı doldurur.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alan adı |
| value | String | Alanın yeni değeri |
| fitFontSize | Boolean | Eğer doğruysa, düzenleme kutularındaki yazı tipi boyutu ayarlanacaktır. |

### Dönüş Değeri

Alan bulunduysa ve başarıyla doldurulduysa doğru.

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Alanı tam nitelikli alan adına göre geçerli bir değerle doldurur. Alanları doldurmadan önce, her alanın adları ve karşılık gelen geçerli değerleri bilinmelidir. Hem alan adları hem de değerler büyük/küçük harf duyarlıdır. Lütfen Aspose.Pdf.Facades'ın yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit ile karşılaştırıldığında kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin, alanın tam adı "Form.Subform.TextField" ise, tam adı belirtmelisiniz ve "TextField" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Doldurulacak alanın adı. |
| fieldValue | String | Alanın değeri, bazı alanlar için geçerli bir değer olmalıdır. |

### Dönüş Değeri

Alan bulunduysa ve başarıyla doldurulduysa doğru.

## Örnekler

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Radyo kutusu alanını tam nitelikli alan adına göre geçerli bir indeks değeriyle doldurur. Alanları doldurmadan önce, yalnızca alan adı bilinmelidir. Değer, indeksine göre belirtilebilir. Not: Sadece Radyo Kutusu, Kombinasyon Kutusu ve Liste Kutusu alanlarına uygulanabilir. Lütfen Aspose.Pdf.Facades'ın yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit ile karşılaştırıldığında kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin, alanın tam adı "Form.Subform.ListBoxField" ise, tam adı belirtmelisiniz ve "ListBoxField" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz.

```csharp
public bool FillField(string fieldName, int index)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Doldurulacak alanın adı. |
| index | Int32 | Seçilen öğenin indeksi. |

### Dönüş Değeri

Alan bulunduysa ve başarıyla doldurulduysa doğru.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Onay kutusu alanını bir boolean değeriyle doldurur. Not: Sadece Onay Kutusu için uygulanabilir. Lütfen Aspose.Pdf.Facades'ın yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit ile karşılaştırıldığında kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin, alanın tam adı "Form.Subform.CheckBoxField" ise, tam adı belirtmelisiniz ve "CheckBoxField" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Doldurulacak alanın adı. |
| beChecked | Boolean | Bir boolean bayrağı: doğru, kutuyu işaretlemek anlamına gelir, yanlış ise işareti kaldırmak anlamına gelir. |

### Dönüş Değeri

Alan bulunduysa ve başarıyla doldurulduysa doğru.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Bir alanı birden fazla seçimle doldurur. Not: yalnızca AcroForm Liste Kutusu Alanı için.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Tam nitelikli alan adı. |
| fieldValues | String[] | Seçilecek birkaç öğe içeren bir dizi. |

## Örnekler

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

Belirtilen değerle alanı doldurur.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alan adı |
| value | String | Alanın yeni değeri |
| fitFontSize | Boolean | Eğer doğruysa, düzenleme kutularındaki yazı tipi boyutu ayarlanacaktır. |

### Dönüş Değeri

Alan bulunduysa ve başarıyla doldurulduysa doğru.

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)