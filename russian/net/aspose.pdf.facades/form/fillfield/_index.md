---
title: FillField
second_title: Aspose.PDF для справочника API .NET
description: Заполняет поле указанным значением.
type: docs
weight: 160
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

true, если поле найдено и успешно заполнено.

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Заполняет поле допустимым значением в соответствии с полным именем поля. Перед заполнением полей необходимо знать имена каждого поля и соответствующие им допустимые значения. И имя поля, и значения чувствительны к регистру. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.TextField", вы должны указать полное имя, а не "Текстовое поле". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля для заполнения. |
| fieldValue | String | Значение поля, которое должно быть допустимым значением для некоторых полей. |

### Возвращаемое значение

true, если поле найдено и заполнено успешно.

### Примеры

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//как искать поле по частичному имени:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Заполняет поле переключателя допустимым значением индекса в соответствии с полным именем поля. Перед заполнением полей необходимо знать только имя поля. Хотя значение может быть указано по его индексу. Примечание: применяется только к полям Radio Box, Combo Box и List Box. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.ListBoxField", вы должны указать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

```csharp
public bool FillField(string fieldName, int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Название поля для заполнения. |
| index | Int32 | Индекс выбранного элемента. |

### Возвращаемое значение

true, если поле найдено и успешно заполнено.

### Примеры

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//как искать поле по частичному имени:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Заполняет поле флажка логическим значением. Примечание: применяется только к флажку. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf .Kit; Например, если поле имеет полное имя "Form.Subform.CheckBoxField", вы должны указать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля для заполнения. |
| beChecked | Boolean | Логический флаг: true означает, что флажок установлен, а false, чтобы его снять. |

### Возвращаемое значение

true, если поле найдено и успешно заполнено.

### Примеры

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//как искать поле по частичному имени:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Заполните поле несколькими вариантами выбора. Примечание: только для поля списка AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |
| fieldValues | String[] | Строковый массив, содержащий несколько элементов для выбора. |

### Примеры

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
