---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Заполняет поле допустимым значением в соответствии с полным именем поля. Перед заполнением полей необходимо знать имена всех полей и соответствующие допустимые значения. Имена полей и значения чувствительны к регистру. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit. Например, если поле имеет полное имя Form.Subform.TextField, вы должны указать полное имя, а не TextField. Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска необходимого поля по его частичному имени.
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Заполняет поле указанным значением.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля |
| value | String | Новое значение поля |
| fitFontSize | Boolean | Если true, размер шрифта в полях редактирования будет подогнан. |

### Возвращаемое значение

true, если поле было найдено и успешно заполнено.

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Заполняет поле допустимым значением в соответствии с полным именем поля. Перед заполнением полей необходимо знать имена всех полей и соответствующие допустимые значения. Имена полей и значения чувствительны к регистру. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.TextField", вы должны указать полное имя, а не "TextField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска необходимого поля по его частичному имени.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое нужно заполнить. |
| fieldValue | String | Значение поля, которое должно быть допустимым значением для некоторых полей. |

### Возвращаемое значение

true, если поле найдено и успешно заполнено.

## Примеры

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

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Заполняет поле радиокнопки допустимым индексом в соответствии с полным именем поля. Перед заполнением полей необходимо знать только имя поля. Значение может быть указано по его индексу. Обратите внимание: применяется только к полям радиокнопок, комбинированным полям и полям списка. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.ListBoxField", вы должны указать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска необходимого поля по его частичному имени.

```csharp
public bool FillField(string fieldName, int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое нужно заполнить. |
| index | Int32 | Индекс выбранного элемента. |

### Возвращаемое значение

true, если поле было найдено и успешно заполнено.

## Примеры

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

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Заполняет поле флажка логическим значением. Обратите внимание: применяется только к полям флажков. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.CheckBoxField", вы должны указать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска необходимого поля по его частичному имени.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое нужно заполнить. |
| beChecked | Boolean | Логический флаг: true означает установить флажок, в то время как false — снять его. |

### Возвращаемое значение

true, если поле было найдено и успешно заполнено.

## Примеры

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

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Заполняет поле несколькими выборами. Примечание: только для поля списка AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |
| fieldValues | String[] | Массив строк, который содержит несколько элементов для выбора. |

## Примеры

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

Заполняет поле указанным значением.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля |
| value | String | Новое значение поля |
| fitFontSize | Boolean | Если true, размер шрифта в полях редактирования будет подогнан. |

### Возвращаемое значение

true, если поле было найдено и успешно заполнено.

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)