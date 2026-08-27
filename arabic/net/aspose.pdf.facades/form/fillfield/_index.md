---
title: "Form.FillField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول يجب معرفة جميع أسماء الحقول والقيم الصالحة المقابلة لها. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن Aspose.Pdf.Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit. على سبيل المثال إذا كان للحقول الاسم الكامل Form.Subform.TextField يجب تحديد الاسم الكامل وليس TextField. يمكنك استخدام الخاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي"
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

يملى الحقل بقيمة صالحة وفقًا لاسم الحقل الكامل المؤهل. قبل ملء الحقول، يجب معرفة أسماء جميع الحقول والقيم الصالحة المقابلة لها. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن **Aspose.Pdf.Facades** يدعم فقط الأسماء الكاملة للحقول ولا يعمل مع الأسماء الجزئية على عكس **Aspose.Pdf.Kit**؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.TextField\" يجب تحديد الاسم الكامل وليس \"TextField\". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم ملؤه. |
| fieldValue | String | قيمة الحقل التي يجب أن تكون قيمة صالحة لبعض الحقول. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وملئه بنجاح.

## أمثلة

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//كيفية البحث عن الحقل باسمه الجزئي:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

يملى حقل صندوق الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل الكامل المؤهل. قبل ملء الحقول، يجب معرفة اسم الحقل فقط. ويمكن تحديد القيمة بواسطة فهرسها. ملاحظة: يُطبق فقط على حقول صندوق الراديو، صندوق القائمة المنسدلة وصندوق القائمة. يرجى ملاحظة أن **Aspose.Pdf.Facades** يدعم فقط الأسماء الكاملة للحقول ولا يعمل مع الأسماء الجزئية على عكس **Aspose.Pdf.Kit**؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.ListBoxField\" يجب تحديد الاسم الكامل وليس \"ListBoxField\". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي.

```csharp
public bool FillField(string fieldName, int index)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم ملؤه. |
| index | Int32 | فهرس العنصر المختار. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وملئه بنجاح.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//كيفية البحث عن الحقل باسمه الجزئي:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

يملى حقل خانة الاختيار بقيمة منطقية. ملاحظة: يُطبق فقط على خانة الاختيار. يرجى ملاحظة أن **Aspose.Pdf.Facades** يدعم فقط الأسماء الكاملة للحقول ولا يعمل مع الأسماء الجزئية على عكس **Aspose.Pdf.Kit**؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.CheckBoxField\" يجب تحديد الاسم الكامل وليس \"CheckBoxField\". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم ملؤه. |
| beChecked | Boolean | علامة منطقية: true تعني تحديد المربع، بينما false تعني إلغاء تحديده. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وملئه بنجاح.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//كيفية البحث عن الحقل باسمه الجزئي:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

املأ حقلًا بتحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |
| fieldValues | String[] | مصفوفة سلسلة تحتوي على عدة عناصر لتحديدها. |

## أمثلة

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

يملى الحقل بالقيمة المحددة.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل |
| القيمة | String | القيمة الجديدة للحقل |
| fitFontSize | Boolean | إذا كان صحيحًا، سيتم تعديل حجم الخط في مربعات التحرير. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وملئه بنجاح.

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


