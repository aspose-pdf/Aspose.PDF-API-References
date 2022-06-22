---
title: Form
second_title: Aspose.PDF для справочника API .NET
description: Класс представляющий объект формы Acro.
type: docs
weight: 2300
url: /ru/net/aspose.pdf.facades/form/
---
## Form class

Класс, представляющий объект формы Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Form](form#constructor)() | Построение формы без параметров.  &lt;code&gt; Form form = new Aspose.Pdf.Facades.Form(); form.SrcFileName = "file.pdf"; &lt;/code&gt; |
| [Form](form#constructor_1)(Document) | Инициализирует новый[`Form`](../form)объект на основе*document*. |
| [Form](form#constructor_4)(Stream) | Конструктор формы. |
| [Form](form#constructor_8)(string) | Конструктор формы. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | Получает или задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | Получает или задает способ сохранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение:inline/attachment. По умолчанию:встроенный. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, то файл будет сохранен в формате PDF по умолчанию без преобразования. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | Получает список имен полей в форме. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | Получает все имена кнопок отправки форм. |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | Результат последней операции импорта. Массив объектов, описывающих результат импорта для каждого поля. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | Получает или задает объект Response, в котором будет храниться результат операции. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию:PdfSaveOptions. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/form/close)() | Закрывает открытые файлы без изменений. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | Экспортирует содержимое полей pdf в поток fdf. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | Извлекает пакет данных XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | Заполните поле штрих-кода в соответствии с его полным именем поля. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | Заполняет поле флажка логическим значением. Примечание:применяется только к флажку. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.CheckBoxField", вы должны указать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | Заполняет поле переключателя допустимым значением индекса в соответствии с полным именем поля. Перед заполнением полей необходимо знать только название поля. В то время как значение может быть указано по его индексу. Примечание. Применяется только к полям Radio Box, Combo Box и List Box. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.ListBoxField", вы должны указать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | Заполняет поле допустимым значением в соответствии с полным именем поля. Перед заполнением полей необходимо знать имена всех полей и соответствующие им допустимые значения. Имя и значение полей чувствительны к регистру. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Форма.Подформа.ТекстовоеПоле", вы должны указать полное имя, а не "ТекстовоеПоле". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | Заполните поле несколькими вариантами выбора. Примечание:только для поля списка AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | Заполняет поле указанным значением. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | Заполняет поля текстового поля текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Примечание:применяется только к текстовому полю. Имя и значение полей чувствительны к регистру. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | Перегружает функцию FillImageField. Вход представляет собой поток изображения. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | Вставляет изображение в существующее поле кнопки как его внешний вид в соответствии с его полным именем поля. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | Выравнивает все поля. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | Выравнивает указанное поле с полным именем поля. Любое другое поле останется неизменным. Если fieldName неверно, все поля останутся неизменными. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | Возвращает текущее значение для полей опций переключателя. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | Получает поля параметров переключателя и связанные значения на основе имени поля. Этот метод имеет значение для групп переключателей. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | Получает значение поля в соответствии с его именем. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | Возвращает объект FrofmFieldFacade, содержащий все атрибуты внешнего вида.  &lt;code&gt; Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf"); FormFieldFacade field = form.GetFieldFacade("field1"); Console.WriteLine("Цвет границы поля:" + field.BorderColor); &lt;/code&gt; |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | Возвращает флаги поля. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | Получить ограничение текстового поля. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | Возвращает тип поля. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | Получает полное имя поля в соответствии с его кратким именем поля. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | Получить значение поля форматированного текста, включая информацию о форматировании каждого символа. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | Возвращает флаги отправки кнопки отправки |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | Импортирует содержимое полей из файла fdf и помещает их в новый pdf. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | Определяет, является ли поле обязательным или нет. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | Переименовывает поле. Подойдет либо поле AcroForm, либо поле XFA. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | Сохраняет документ в указанный поток. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | Сохраняет документ в указанный файл. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | Заменяет данные XFA указанным пакетом данных. Пакет данных может быть извлечен с помощью ExtractXfaData. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [FormImportResult](form.formimportresult) | Класс, описывающий результат импорта поля. |
| enum [ImportStatus](form.importstatus) | Состояние импортированного поля |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
