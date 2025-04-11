---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.Form. Класс, представляющий объект Acro формы
type: docs
weight: 4290
url: /ru/net/aspose.pdf.facades/form/
---
## Класс Form

Класс, представляющий объект Acro формы.

```csharp
public sealed class Form : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Form](form/#constructor)() | Конструктор Form без параметров. |
| [Form](form/#constructor_1)(Document) | Инициализирует новый объект `Form` на основе *документа*. |
| [Form](form/#constructor_4)(Stream) | Конструктор для формы. |
| [Form](form/#constructor_7)(string) | Конструктор Form. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Устанавливает формат PDF файла. Результирующий файл будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без конвертации. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Получает список имен полей на форме. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Получает все имена кнопок отправки формы. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Результат последней операции импорта. Массив объектов, описывающих результат импорта для каждого поля. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Закрывает открытые файлы без каких-либо изменений. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Уничтожает фасад. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Экспортирует содержимое полей pdf в поток fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Экспортирует содержимое всех полей в документе в поток JSON. Значения полей кнопок не экспортируются. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Извлекает пакет данных XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Заполняет поле штрих-кода в соответствии с его полным именем поля. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Заполняет поле флажка логическим значением. Обратите внимание: применяется только к полю Check Box. Пожалуйста, обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.CheckBoxField", вы должны указать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames, чтобы исследовать существующие имена полей и искать требуемое поле по его частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Заполняет поле радиокнопки допустимым индексом в соответствии с полным именем поля. Перед заполнением полей должно быть известно только имя поля. Значение может быть указано по его индексу. Обратите внимание: применяется только к полям Radio Box, Combo Box и List Box. Пожалуйста, обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.ListBoxField", вы должны указать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames, чтобы исследовать существующие имена полей и искать требуемое поле по его частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Заполняет поле допустимым значением в соответствии с полным именем поля. Перед заполнением полей должны быть известны имена каждого поля и соответствующие допустимые значения. Имена полей и значения чувствительны к регистру. Пожалуйста, обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.TextField", вы должны указать полное имя, а не "TextField". Вы можете использовать свойство FieldNames, чтобы исследовать существующие имена полей и искать требуемое поле по его частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Заполняет поле несколькими выборами. Примечание: только для поля списка AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Заполняет поле указанным значением. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Заполняет текстовые поля текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Обратите внимание: применяется только к Text Box. Имена полей и значения чувствительны к регистру. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Перегружает функцию FillImageField. Входные данные - это поток изображения. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Вставляет изображение на существующее поле кнопки в качестве его внешнего вида в соответствии с полным именем поля. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Уплощает все поля. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Уплощает указанное поле с полным именем поля. Любое другое поле останется неизменным. Если имя поля недействительно, все поля останутся неизменными. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Возвращает текущее значение для полей опций радиокнопки. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Получает поля опций радиокнопки и связанные значения на основе имени поля. Этот метод имеет значение для групп радиокнопок. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Получает значение поля в соответствии с его именем поля. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Возвращает объект FrofmFieldFacade, содержащий все атрибуты внешнего вида. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Возвращает флаги поля. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Получает ограничение текстового поля. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Возвращает тип поля. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Получает полное имя поля в соответствии с его коротким именем поля. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Получает значение поля Rich Text, включая информацию о форматировании каждого символа. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Возвращает флаги отправки кнопки отправки |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Импортирует содержимое полей из файла fdf и помещает их в новый pdf. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Импортирует все данные полей из потока JSON в поля документа, сопоставляя поля по их полным именам. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Определяет, является ли поле обязательным или нет. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Переименовывает поле. Подходит как для полей AcroForm, так и для полей XFA. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Сохраняет документ в указанный поток. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Сохраняет документ в указанный файл. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Заменяет данные XFA на указанный пакет данных. Пакет данных может быть извлечен с помощью ExtractXfaData. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Класс, который описывает результат импорта поля. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Статус импортированного поля |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)