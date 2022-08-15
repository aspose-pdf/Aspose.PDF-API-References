---
title: FillField
second_title: Aspose.PDF لمرجع .NET API
description: يملأ الحقل بقيمة محددة.
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

يملأ الحقل بقيمة محددة.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم المجال |
| value | String | القيمة الجديدة للحقل |
| fitFontSize | Boolean | إذا كان هذا صحيحًا ، فسيتم تعديل حجم الخط في مربعات التحرير. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

يملأ الحقل بقيمة صالحة وفقًا لاسم حقل مؤهل بالكامل. قبل ملء الحقول ، يجب معرفة أسماء كل حقل والقيم الصالحة المقابلة له. كل من اسم الحقول وقيمها حساسة لحالة الأحرف. Aspose.Pdf.Facades يدعم أسماء الحقول الكاملة فقط ولا يعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit على سبيل المثال إذا كان الحقل يحتوي على الاسم الكامل "Form.Subform.TextField" ، يجب عليك تحديد الاسم الكامل وليس "مجال التحرير مكان كتابة النص". يمكنك استخدام خاصية أسماء الحقول لاستكشاف أسماء الحقول الموجودة والبحث في الحقل المطلوب باسمه الجزئي.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المراد تعبئته. |
| fieldValue | String | قيمة الحقل التي يجب أن تكون قيمة صالحة لبعض الحقول. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

### أمثلة

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
// كيفية البحث عن الحقل باسمه الجزئي:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

يملأ حقل مربع الراديو بقيمة فهرس صالحة وفقًا لاسم حقل مؤهل بالكامل. قبل ملء الحقول ، يجب معرفة اسم الحقل فقط. بينما يمكن تحديد القيمة من خلال فهرسها. إشعار: يتم تطبيقه فقط على حقول Radio Box و Combo Box و List Box . يرجى ملاحظة أن Aspose.Pdf.Facades يدعم أسماء الحقول الكاملة فقط ولا يعمل مع أسماء الحقول الجزئية على النقيض من Aspose.Pdf.Kit على سبيل المثال إذا كان الحقل يحتوي على الاسم الكامل "Form.Subform.ListBoxField" يجب عليك تحديد الاسم الكامل وليس "ListBoxField". يمكنك استخدام خاصية أسماء الحقول لاستكشاف أسماء الحقول الموجودة والبحث في الحقل المطلوب باسمه الجزئي.

```csharp
public bool FillField(string fieldName, int index)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المراد تعبئته. |
| index | Int32 | فهرس العنصر المختار. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

### أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
// كيفية البحث عن الحقل باسمه الجزئي:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

يملأ حقل خانة الاختيار بقيمة منطقية. ملاحظة: يتم تطبيقه على خانة الاختيار فقط. يرجى ملاحظة أن Aspose.Pdf.Facades يدعم أسماء الحقول الكاملة فقط ولا يعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf .Kit على سبيل المثال إذا كان الحقل يحتوي على الاسم الكامل "Form.Subform.CheckBoxField" ، يجب عليك تحديد الاسم الكامل وليس "CheckBoxField". يمكنك استخدام خاصية أسماء الحقول لاستكشاف أسماء الحقول الموجودة والبحث في الحقل المطلوب باسمه الجزئي.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المراد تعبئته. |
| beChecked | Boolean | علم منطقي: صحيح يعني تحديد المربع ، بينما يعني الخطأ إلغاء تحديده. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وتم ملؤه بنجاح.

### أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
// كيفية البحث عن الحقل باسمه الجزئي:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

قم بتعبئة الحقل بالعديد من التحديدات. ملاحظة: فقط لحقل قائمة AcroForm .

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |
| fieldValues | String[] | مصفوفة سلسلة تحتوي على عدة عناصر ليتم تحديدها. |

### أمثلة

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
