---
title: "Класс Form"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.Form. Класс, представляющий объект Acro формы"
type: docs
weight: 4410
url: /ru/net/aspose.pdf.facades/form/
---
## Form class

Класс, представляющий объект Acro формы.

```csharp
public sealed class Form : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Form](form/#constructor)() | Конструктор Form без параметров. |
| [Form](form/#constructor_1)(Document) | Инициализирует новый объект `Form` на основе *document*. |
| [Form](form/#constructor_4)(Stream) | Конструктор формы. |
| [Form](form/#constructor_7)(string) | Конструктор Form. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Устанавливает формат PDF‑файла. Результирующий файл будет сохранён в указанном формате. Если это свойство не указано, файл будет сохранён в формате PDF по умолчанию без конвертации. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Получает список имён полей в форме. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Получает имена всех кнопок отправки формы. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Результат последней операции импорта. Массив объектов, описывающих результат импорта для каждого поля. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Закрывает открытые файлы без каких-либо изменений. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Экспортирует содержимое полей pdf в поток fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Экспортирует содержимое всех полей документа в поток JSON. Значения полей кнопок не экспортируются. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Извлекает пакет данных XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Заполняет поле штрихкода в соответствии с его полностью квалифицированным именем. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Заполняет поле флажка булевым значением. Примечание: применяется только к полю Check Box. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами, в отличие от Aspose.Pdf.Kit; например, если у поля полное имя \"Form.Subform.CheckBoxField\", следует указывать полное имя, а не \"CheckBoxField\". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска требуемого поля по его частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Заполняет поле радиокнопки допустимым индексным значением в соответствии с полностью квалифицированным именем поля. Перед заполнением необходимо знать только имя поля. Значение может быть указано по его индексу. Примечание: применяется только к полям Radio Box, Combo Box и List Box. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами, в отличие от Aspose.Pdf.Kit; например, если у поля полное имя \"Form.Subform.ListBoxField\", следует указывать полное имя, а не \"ListBoxField\". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска требуемого поля по его частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Заполняет поле допустимым значением в соответствии с полностью квалифицированным именем поля. Перед заполнением необходимо знать имена всех полей и их соответствующие допустимые значения. И имена полей, и значения чувствительны к регистру. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами, в отличие от Aspose.Pdf.Kit; например, если у поля полное имя \"Form.Subform.TextField\", следует указывать полное имя, а не \"TextField\". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска требуемого поля по его частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Заполняет поле несколькими выборами. Примечание: только для поля AcroForm List Box. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Заполняет поле указанным значением. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Заполняет поля текстового поля текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Примечание: применяется только к полю Text Box. И имена полей, и значения чувствительны к регистру. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Перегружает функцию FillImageField. Входные данные — поток изображения. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Вставляет изображение в существующее поле кнопки в качестве его внешнего вида в соответствии с полностью квалифицированным именем поля. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Преобразует все поля в плоские. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Преобразует указанное поле с полностью квалифицированным именем в плоское. Все остальные поля останутся неизменными. Если fieldName недействителен, все поля останутся неизменными. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Возвращает текущее значение для полей вариантов радиокнопок. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Получает поля вариантов радиокнопок и связанные значения по имени поля. Этот метод имеет смысл для групп радиокнопок. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Получает значение поля по его имени. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Возвращает объект FrofmFieldFacade, содержащий все атрибуты внешнего вида. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Возвращает флаги поля. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Получает ограничения текстового поля. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Возвращает тип поля. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Получает полное имя поля по его короткому имени. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Получает значение поля Rich Text, включая информацию о форматировании каждого символа. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Возвращает флаги отправки кнопки submit |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Импортирует содержимое полей из файла fdf и помещает их в новый pdf. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Импортирует все данные полей из потока JSON в поля документа, сопоставляя поля по их полным именам. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Определяет, является ли поле обязательным. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Переименовывает поле. Подходит как поле AcroForm, так и поле XFA. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Сохраняет документ в указанный поток. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Сохраняет документ в указанный файл. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Заменяет данные XFA указанным пакетом данных. Пакет данных может быть извлечён с помощью ExtractXfaData. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Класс, описывающий результат импорта поля. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Состояние импортированного поля |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


