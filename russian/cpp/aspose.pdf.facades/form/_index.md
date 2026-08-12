---
title: "Aspose::Pdf::Facades::Form класс"
linktitle: "Form"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::Form класс. Класс, представляющий объект Acro формы в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.facades/form/
---
## Form class


Класс, представляющий объект Acro-формы.

```cpp
class Form : public Aspose::Pdf::Facades::SaveableFacade
```

## Nested classes

* Class [FormImportResult](./formimportresult/)
## Enums

| Перечисление | Описание |
| --- | --- |
| [ImportStatus](./importstatus/) | Состояние импортированного поля. |
## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Закрывает открытые файлы без каких-либо изменений. |
| [ExportFdf](./exportfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Экспортирует содержимое полей PDF в поток FDF. |
| [ExportXfdf](./exportxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Экспортирует содержимое полей PDF в XML‑поток. Значение поля кнопки не будет экспортировано. |
| [ExportXml](./exportxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Экспортирует содержимое полей PDF в XML‑поток. Значение поля кнопки не будет экспортировано. |
| [ExtractXfaData](./extractxfadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Извлекает пакет данных XFA. |
| [FillBarcodeField](./fillbarcodefield/)(const System::String\&, const System::String\&) | Заполняет поле штрих‑кода согласно его полностью квалифицированному имени поля. |
| [FillField](./fillfield/)(const System::String\&, const System::String\&) | Заполняет поле допустимым значением согласно полностью квалифицированному имени поля. Перед заполнением полей необходимо знать все имена полей и их соответствующие допустимые значения. И имена полей, и значения чувствительны к регистру. Обратите внимание, что [Aspose.Pdf.Facades](../) поддерживает только полные имена полей и не работает с частичными именами, в отличие от Aspose.Pdf.Kit; например, если у поля полное имя "Form.Subform.TextField", следует указывать полное имя, а не "TextField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска требуемого поля по его частичному имени. |
| [FillField](./fillfield/)(const System::String\&, int32_t) | Заполняет поле радиокнопки допустимым индексным значением согласно полностью квалифицированному имени поля. Перед заполнением полей необходимо знать только имя поля. Значение может быть указано по его индексу. Примечание: применяется только к полям Radio Box, Combo Box и List Box. Обратите внимание, что [Aspose.Pdf.Facades](../) поддерживает только полные имена полей и не работает с частичными именами, в отличие от Aspose.Pdf.Kit; например, если у поля полное имя "Form.Subform.ListBoxField", следует указывать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска требуемого поля по его частичному имени. |
| [FillField](./fillfield/)(const System::String\&, bool) | Заполняет поле флажка булевым значением. Примечание: применяется только к полю Check Box. Обратите внимание, что [Aspose.Pdf.Facades](../) поддерживает только полные имена полей и не работает с частичными именами, в отличие от Aspose.Pdf.Kit; например, если у поля полное имя "Form.Subform.CheckBoxField", следует указывать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames для изучения существующих имен полей и поиска требуемого поля по его частичному имени. |
| [FillField](./fillfield/)(const System::String\&, const System::ArrayPtr\<System::String\>\&) | Заполняет поле несколькими выборами. Примечание: только для поля AcroForm List Box. |
| [FillField](./fillfield/)(const System::String\&, const System::String\&, bool) | Заполняет поле указанным значением. |
| [FillFields](./fillfields/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<System::String\>\&, System::SharedPtr\<System::IO::Stream\>\&) | Заполняет поля текстовых полей текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Примечание: применяется только к [Text](../../aspose.pdf.text/) Box. И имена полей, и значения чувствительны к регистру. |
| [FillImageField](./fillimagefield/)(const System::String\&, const System::String\&) | Вставляет изображение в существующее поле кнопки в качестве его внешнего вида согласно полностью квалифицированному имени поля. |
| [FillImageField](./fillimagefield/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Перегружает функцию FillImageField. Входные данные — поток изображения. |
| [FlattenAllFields](./flattenallfields/)() | Преобразует все поля в плоские. |
| [FlattenField](./flattenfield/)(const System::String\&) | Преобразует в плоское указанное поле по полностью квалифицированному имени. Все остальные поля останутся неизменными. Если fieldName недействительно, все поля останутся неизменными. |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Конструктор [Form](./) с двумя параметрами‑потоками. Укажите одинаковый исходный и целевой поток для инкрементного обновления. |
| [Form](./form/)() | Конструктор [Form](./) без параметров. |
| [Form](./form/)(const System::String\&) | Конструктор [Form](./). |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&) | Конструктор формы. |
| [Form](./form/)(const System::String\&, const System::String\&) | Конструктор класса [Form](./). Укажите одинаковое имя исходного и целевого файла для выполнения инкрементного обновления. |
| [Form](./form/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Конструктор [Form](./). |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Конструктор [Form](./). |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [Form](./) на основе *document* . |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Инициализирует новый объект [Form](./) на основе *document* . |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Инициализирует новый объект [Form](./) на основе *document* . |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Создаёт форму, которая сохранит результат в объект HttpResponse. |
| [Form](./form/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Создаёт форму, которая сохранит результат в объект HttpResponse. |
| [get_AttachmentName](./get_attachmentname/)() const | Получает имя вложения, когда результат операции сохраняется в объекты HttpResponse в виде вложения. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Получает способ хранения содержимого, когда результат операции сохраняется в объект HttpResponse. Возможные значения: inline / attachment. По умолчанию: inline. |
| [get_DestFileName](./get_destfilename/)() const | Получает имя файла назначения. |
| [get_DestStream](./get_deststream/)() const | Получает целевой поток. |
| [get_FieldNames](./get_fieldnames/)() | Получает список имён полей в форме. |
| [get_FormSubmitButtonNames](./get_formsubmitbuttonnames/)() | Получает все имена кнопок отправки формы. |
| [get_ImportResult](./get_importresult/)() | Результат последней операции импорта. Массив объектов, описывающих результат импорта для каждого поля. |
| [get_Response](./get_response/)() const | Получает объект Response, в котором будет сохранён результат операции. |
| [get_SaveOptions](./get_saveoptions/)() const | Получает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Получает имя исходного файла. |
| [get_SrcStream](./get_srcstream/)() const | Получает исходный поток. |
| [GetButtonOptionCurrentValue](./getbuttonoptioncurrentvalue/)(const System::String\&) | Возвращает текущее значение для полей вариантов радиокнопок. |
| [GetButtonOptionValues](./getbuttonoptionvalues/)(const System::String\&) | Получает поля вариантов радиокнопок и связанные значения на основе имени поля. Этот метод имеет смысл для групп радиокнопок. |
| [GetField](./getfield/)(const System::String\&) | Получает значение поля согласно его имени. |
| [GetFieldFacade](./getfieldfacade/)(const System::String\&) | Возвращает объект FrofmFieldFacade, содержащий все атрибуты отображения. |
| [GetFieldFlag](./getfieldflag/)(const System::String\&) | Возвращает флаги поля. |
| [GetFieldLimit](./getfieldlimit/)(const System::String\&) | Получить ограничение текстового поля. |
| [GetFieldType](./getfieldtype/)(const System::String\&) | Возвращает тип поля. |
| [GetFullFieldName](./getfullfieldname/)(const System::String\&) | Получает полное имя поля согласно его короткому имени. |
| [GetRichText](./getrichtext/)(const System::String\&) | Получить значение поля Rich [Text](../../aspose.pdf.text/), включая информацию о форматировании каждого символа. |
| [GetSubmitFlags](./getsubmitflags/)(const System::String\&) | Возвращает флаги отправки кнопки submit. |
| [ImportFdf](./importfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Импортирует содержимое полей из файла fdf и помещает их в новый pdf. |
| [ImportXfdf](./importxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf. |
| [ImportXml](./importxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [ImportXml](./importxml/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Импортирует содержимое полей из файла xml и помещает их в новый pdf. |
| [IsRequiredField](./isrequiredfield/)(const System::String\&) | Определяет, является ли поле обязательным. |
| [RenameField](./renamefield/)(const System::String\&, const System::String\&) | Переименовывает поле. Подходит как поле AcroForm, так и поле XFA. |
| [Save](./save/)() | Сохраняет значение заполненных полей и закрывает открытый документ [Pdf](../../aspose.pdf/). |
| [Save](./save/)(System::String) override | Сохраняет документ в указанный файл. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет документ в указанный поток. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Устанавливает имя вложения, когда результат операции сохраняется в объекты HttpResponse в виде вложения. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Устанавливает способ хранения содержимого, когда результат операции сохраняется в объект HttpResponse. Возможные значения: inline / attachment. По умолчанию: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Устанавливает формат PDF‑файла. Результирующий файл будет сохранён в указанном формате. Если это свойство не указано, файл будет сохранён в формате PDF по умолчанию без конвертации. |
| [set_DestFileName](./set_destfilename/)(const System::String\&) | Устанавливает имя файла назначения. |
| [set_DestStream](./set_deststream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает целевой поток. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Устанавливает объект Response, в котором будет сохранён результат операции. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Устанавливает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(const System::String\&) | Устанавливает имя исходного файла. |
| [set_SrcStream](./set_srcstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает исходный поток. |
| [SetXfaData](./setxfadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Заменяет данные XFA указанным пакетом данных. Пакет данных может быть извлечён с помощью ExtractXfaData. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
