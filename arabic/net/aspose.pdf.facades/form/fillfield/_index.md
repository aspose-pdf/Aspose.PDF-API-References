---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب معرفة أسماء جميع الحقول والقيم الصالحة المقابلة لها. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن Aspose.Pdf.Facades تدعم فقط أسماء الحقول الكاملة ولا تعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit. على سبيل المثال، إذا كان الحقل يحمل الاسم الكامل Form.Subform.TextField، يجب عليك تحديد الاسم الكامل وليس TextField. يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب حسب اسمه الجزئي.
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

يملأ الحقل بالقيمة المحددة.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل |
| value | String | القيمة الجديدة للحقل |
| fitFontSize | Boolean | إذا كانت صحيحة، سيتم ضبط حجم الخط في صناديق التحرير. |

### Return Value

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب معرفة أسماء جميع الحقول والقيم الصالحة المقابلة لها. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن Aspose.Pdf.Facades تدعم فقط أسماء الحقول الكاملة ولا تعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال، إذا كان الحقل يحمل الاسم الكامل "Form.Subform.TextField"، يجب عليك تحديد الاسم الكامل وليس "TextField". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب حسب اسمه الجزئي.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم ملؤه. |
| fieldValue | String | قيمة الحقل التي يجب أن تكون قيمة صالحة لبعض الحقول. |

### Return Value

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

## Examples

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

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

يملأ حقل مربع الاختيار بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب معرفة اسم الحقل فقط. بينما يمكن تحديد القيمة بواسطة فهرسها. ملاحظة: ينطبق فقط على حقول مربع الاختيار، ومربع التحرير، ومربع القائمة. يرجى ملاحظة أن Aspose.Pdf.Facades تدعم فقط أسماء الحقول الكاملة ولا تعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال، إذا كان الحقل يحمل الاسم الكامل "Form.Subform.ListBoxField"، يجب عليك تحديد الاسم الكامل وليس "ListBoxField". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب حسب اسمه الجزئي.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم ملؤه. |
| index | Int32 | فهرس العنصر المختار. |

### Return Value

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

## Examples

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

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

يملأ حقل مربع الاختيار بقيمة منطقية. ملاحظة: ينطبق فقط على مربع الاختيار. يرجى ملاحظة أن Aspose.Pdf.Facades تدعم فقط أسماء الحقول الكاملة ولا تعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال، إذا كان الحقل يحمل الاسم الكامل "Form.Subform.CheckBoxField"، يجب عليك تحديد الاسم الكامل وليس "CheckBoxField". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب حسب اسمه الجزئي.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم ملؤه. |
| beChecked | Boolean | علامة منطقية: صحيح تعني التحقق من المربع، بينما خطأ تعني إلغاء التحقق منه. |

### Return Value

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

## Examples

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

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

املأ حقلًا مع تحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |
| fieldValues | String[] | مصفوفة سلسلة تحتوي على عدة عناصر ليتم اختيارها. |

## Examples

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

يملأ الحقل بالقيمة المحددة.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل |
| value | String | القيمة الجديدة للحقل |
| fitFontSize | Boolean | إذا كانت صحيحة، سيتم ضبط حجم الخط في صناديق التحرير. |

### Return Value

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)