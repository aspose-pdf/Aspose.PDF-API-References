---
title: "Метод Aspose::Pdf::Facades::Form::FillField"
linktitle: "FillField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::Form::FillField. Заполняет поле флажка логическим значением. Примечание: применяется только к полям Check Box. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами в отличие от Aspose.Pdf.Kit; например, если у поля полное имя \"Form.Subform.CheckBoxField\", следует указывать полное имя, а не \"CheckBoxField\". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска требуемого поля по его частичному имени в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.facades/form/fillfield/
---
## Form::FillField(const System::String\&, bool) method


Заполняет поле флажка логическим значением. Примечание: применяется только к полям Check Box. Обратите внимание, что [Aspose.Pdf.Facades](../../) поддерживает только полные имена полей и не работает с частичными именами в отличие от Aspose.Pdf.Kit; например, если у поля полное имя "Form.Subform.CheckBoxField", следует указывать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска требуемого поля по его частичному имени.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, bool beChecked)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Имя поля, которое нужно заполнить. |
| beChecked | bool | Логический флаг: true означает установить галочку, а false — снять её. |

### ReturnValue

true, если поле найдено и успешно заполнено.

## См. также

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::ArrayPtr\<System::String\>\&) method


Заполняет поле несколькими выборами. Примечание: только для поля AcroForm List Box.

```cpp
void Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::ArrayPtr<System::String> &fieldValues)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Полностью квалифицированное имя поля. |
| fieldValues | const System::ArrayPtr\<System::String\>\& | Массив строк, содержащий несколько элементов для выбора. |

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::String\&) method


Заполняет поле допустимым значением в соответствии с полностью квалифицированным именем поля. Перед заполнением полей необходимо знать имена всех полей и их соответствующие допустимые значения. И имена полей, и значения чувствительны к регистру. Обратите внимание, что [Aspose.Pdf.Facades](../../) поддерживает только полные имена полей и не работает с частичными именами в отличие от Aspose.Pdf.Kit; например, если у поля полное имя "Form.Subform.TextField", следует указывать полное имя, а не "TextField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска требуемого поля по его частичному имени.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::String &fieldValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Имя поля, которое нужно заполнить. |
| fieldValue | const System::String\& | Значение поля, которое должно быть допустимым для некоторых полей. |

### ReturnValue

true, если поле найдено и успешно заполнено.

## См. также

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, const System::String\&, bool) method


Заполняет поле указанным значением.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, const System::String &value, bool fitFontSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Имя поля |
| value | const System::String\& | Новое значение поля |
| fitFontSize | bool | Если true, размер шрифта в полях ввода будет подогнан. |

### ReturnValue

true, если поле найдено и успешно заполнено.

## См. также

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(const System::String\&, int32_t) method


Заполняет поле радиокнопки действительным индексным значением в соответствии с полностью квалифицированным именем поля. Перед заполнением полей должно быть известно только имя поля. При этом значение может быть указано его индексом. Примечание: применяется только к полям Radio Box, Combo Box и List Box. Обратите внимание, что [Aspose.Pdf.Facades](../../) поддерживает только полные имена полей и не работает с частичными именами полей, в отличие от Aspose.Pdf.Kit; например, если у поля полное имя "Form.Subform.ListBoxField", следует указывать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска нужного поля по его частичному имени.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(const System::String &fieldName, int32_t index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Имя поля для заполнения. |
| индекс | int32_t | Индекс выбранного элемента. |

### ReturnValue

true, если поле найдено и успешно заполнено.
## Примечания




```cpp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```cpp
//как искать поле по его частичному имени:
Form form = new Form("input.pdf", "output.pdf");
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

## См. также

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
