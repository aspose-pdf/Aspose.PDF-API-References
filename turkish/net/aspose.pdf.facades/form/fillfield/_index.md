---
title: FillField
second_title: Aspose.PDF for .NET API Referansı
description: Alanı belirtilen değerle doldurur.
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Alanı belirtilen değerle doldurur.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Alanın adı |
| value | String | Alanın yeni değeri |
| fitFontSize | Boolean | Doğruysa, düzenleme kutularındaki yazı tipi boyutu sığacaktır. |

### Geri dönüş değeri

alan bulunur ve başarıyla doldurulursa true .

### Ayrıca bakınız

* class [Form](../../form)
* ad alanı [Aspose.Pdf.Facades](../../form)
* toplantı [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Alanı, tam nitelikli alan adına göre geçerli bir değerle doldurur. Alanları doldurmadan önce, her alanın adı ve buna karşılık gelen geçerli değerleri bilinmelidir. Hem alanların adı hem de değerleri büyük/küçük harf duyarlıdır. Lütfen şunu unutmayın: Aspose.Pdf.Facades yalnızca tam alan adlarını destekler ve Aspose.Pdf.Kit; 'nin aksine kısmi alan adlarıyla çalışmaz. "Metin alanı". Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Doldurulacak alanın adı. |
| fieldValue | String | Bazı alanlar için geçerli bir değer olması gereken alanın değeri. |

### Geri dönüş değeri

alan bulunur ve başarıyla doldurulursa true .

### Örnekler

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
// alan adı kısmi adıyla nasıl aranır:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ayrıca bakınız

* class [Form](../../form)
* ad alanı [Aspose.Pdf.Facades](../../form)
* toplantı [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Radyo kutusu alanını tam nitelikli alan adına göre geçerli bir dizin değeriyle doldurur. Alanları doldurmadan önce yalnızca alanın adının bilinmesi gerekir. Değer, indeksi ile belirtilebilirken. Uyarı: Yalnızca Radio Box, Combo Box ve List Box alanlarına uygulanabilir. Aspose.Pdf.Facades'in yalnızca tam alan adlarını desteklediğini ve kısmi alan adlarıyla çalışmadığını lütfen unutmayın. Aspose.Pdf.Kit'in aksine; Örneğin, alanın tam adı "Form.Subform.ListBoxField" ise, "ListBoxField" yerine tam adı belirtmelisiniz. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz.

```csharp
public bool FillField(string fieldName, int index)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Doldurulacak alanın adı. |
| index | Int32 | Seçilen öğenin dizini. |

### Geri dönüş değeri

alan bulunur ve başarıyla doldurulursa true .

### Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
// alan adı kısmi adıyla nasıl aranır:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ayrıca bakınız

* class [Form](../../form)
* ad alanı [Aspose.Pdf.Facades](../../form)
* toplantı [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Onay kutusu alanını bir boole değeriyle doldurur. Uyarı: Yalnızca Check Box'a uygulanır. Lütfen unutmayın, Aspose.Pdf.Facades yalnızca tam alan adlarını destekler ve Aspose.Pdf'nin aksine kısmi alan adlarıyla çalışmaz .Kit; Örneğin, alanın tam adı "Form.Subform.CheckBoxField" ise, "CheckBoxField" yerine tam adı belirtmelisiniz. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Doldurulacak alanın adı. |
| beChecked | Boolean | Boolean flag: true, kutuyu işaretlemek, false ise işaretini kaldırmak anlamına gelir. |

### Geri dönüş değeri

alan bulunur ve başarıyla doldurulursa true .

### Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
// alan adı kısmi adıyla nasıl aranır:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Ayrıca bakınız

* class [Form](../../form)
* ad alanı [Aspose.Pdf.Facades](../../form)
* toplantı [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Bir alanı birden çok seçimle doldurun.Not: yalnızca AcroForm Liste Kutusu Alanı için.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Tam nitelikli alan adı. |
| fieldValues | String[] | Seçilecek birkaç öğeyi içeren bir dize dizisi. |

### Örnekler

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Ayrıca bakınız

* class [Form](../../form)
* ad alanı [Aspose.Pdf.Facades](../../form)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
