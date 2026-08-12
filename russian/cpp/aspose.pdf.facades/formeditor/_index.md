---
title: "Класс Aspose::Pdf::Facades::FormEditor"
linktitle: "FormEditor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Facades::FormEditor. Класс для редактирования форм (добавление/удаление полей и т.д.) в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf.facades/formeditor/
---
## FormEditor class


Класс для редактирования форм (добавление/удаление полей и т.д.)

```cpp
class FormEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddField](./addfield/)(FieldType, const System::String\&, int32_t, float, float, float, float) | Добавить поле указанного типа в форму. |
| [AddField](./addfield/)(FieldType, const System::String\&, const System::String\&, int32_t, float, float, float, float) | Добавить поле указанного типа в форму. |
| [AddFieldScript](./addfieldscript/)(const System::String\&, const System::String\&) | Добавить JavaScript для поля PushButton. Если старое событие существует, новое событие добавляется после него. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::String\&) | Добавляет новый элемент в список. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::ArrayPtr\<System::String\>\&) | Добавить новый элемент с экспортным значением в существующее поле списка, только для поля комбобокса AcroForm. |
| [AddSubmitBtn](./addsubmitbtn/)(const System::String\&, int32_t, const System::String\&, const System::String\&, float, float, float, float) | Добавить кнопку отправки в форму. |
| [Close](./close/)() override | Закрывает фасад. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t) | Копирует существующее поле в то же положение на указанной странице. Будет создан новый документ, содержащий всё, что есть в исходном документе, за исключением только что скопированного поля. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Копирует существующее поле в новое положение, указанное номером страницы и координатами. Будет создан новый документ, содержащий всё, что есть в исходном документе, за исключением только что скопированного поля. |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&) | Копирует существующее поле из одного PDF‑документа в другой документ с оригинальными номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t) | Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и оригинальными координатами. Примечание: только для полей AcroForm (исключая переключатели). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели). |
| [DecorateField](./decoratefield/)(const System::String\&) | Изменяет визуальные атрибуты указанного поля. |
| [DecorateField](./decoratefield/)(FieldType) | Изменяет визуальные атрибуты всех полей указанного типа. |
| [DecorateField](./decoratefield/)() | Изменяет визуальные атрибуты всех полей в PDF‑документе. |
| [DelListItem](./dellistitem/)(const System::String\&, const System::String\&) | Удалить элемент из списка. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Конструктор для [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::String\&, const System::String\&) | Конструктор для [FormEditor](./). |
| [FormEditor](./formeditor/)() | Конструктор для [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [FormEditor](./) на основе *document*. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Инициализирует новый объект [FormEditor](./) на основе *document*. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Инициализирует новый объект [FormEditor](./) на основе *document*. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Создаёт [FormEditor](./), который сохранит результат в объект HttpResponse. |
| [FormEditor](./formeditor/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Создаёт [FormEditor](./), который сохранит результат в объект HttpResponse. |
| [get_AttachmentName](./get_attachmentname/)() const | Получает имя вложения, когда результат операции сохраняется в объекты HttpResponse в виде вложения. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Получает способ хранения содержимого, когда результат операции сохраняется в объект HttpResponse. Возможные значения: inline / attachment. По умолчанию: inline. |
| [get_DestFileName](./get_destfilename/)() const | Получает имя целевого файла. |
| [get_DestStream](./get_deststream/)() const | Получает целевой поток. |
| [get_ExportItems](./get_exportitems/)() const | Устанавливает параметры для комбобокса с экспортируемыми значениями. |
| [get_Facade](./get_facade/)() const | Устанавливает визуальные атрибуты поля. |
| [get_Items](./get_items/)() const | Устанавливает элементы, которые будут добавлены в только что созданный список или комбобокс. |
| [get_RadioButtonItemSize](./get_radiobuttonitemsize/)() const | Получает размер элемента радиокнопки (когда добавляется новое поле радиокнопки). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField([FieldType.Radio](../fieldtype/), "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [get_RadioGap](./get_radiogap/)() | Член, фиксирующий промежуток между двумя соседними радиокнопками в пикселях, по умолчанию 50. |
| [get_RadioHoriz](./get_radiohoriz/)() const | Флаг, указывающий, расположены ли радиокнопки горизонтально или вертикально, значение по умолчанию — true. |
| [get_Response](./get_response/)() const | Получает объект Response, в котором будет сохранён результат операции. |
| [get_SaveOptions](./get_saveoptions/)() const | Получает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Получает имя исходного файла. |
| [get_SrcStream](./get_srcstream/)() const | Получает исходный поток. |
| [get_SubmitFlag](./get_submitflag/)() const | Устанавливает флаги отправки для кнопки submit. |
| [GetFieldAppearance](./getfieldappearance/)(const System::String\&) | Получает флаги поля. |
| [MoveField](./movefield/)(const System::String\&, float, float, float, float) | Устанавливает новое положение поля. |
| [RemoveField](./removefield/)(const System::String\&) | Удаляет поле из формы. |
| [RemoveFieldAction](./removefieldaction/)(const System::String\&) | Удаляет действие отправки у поля. |
| [RenameField](./renamefield/)(const System::String\&, const System::String\&) | Изменяет имя поля. |
| [ResetFacade](./resetfacade/)() | Сбрасывает все визуальные атрибуты в пустое значение. |
| [ResetInnerFacade](./resetinnerfacade/)() | Сбрасывает все визуальные атрибуты внутреннего фасада в пустое значение. |
| [Save](./save/)() | Сохраняет изменения в целевой файл. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Устанавливает имя вложения, когда результат операции сохраняется в объекты HttpResponse в виде вложения. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Устанавливает способ хранения содержимого, когда результат операции сохраняется в объект HttpResponse. Возможные значения: inline / attachment. По умолчанию: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Устанавливает формат PDF‑файла. Результирующий файл будет сохранён в указанном формате. Если это свойство не указано, файл будет сохранён в формате PDF по умолчанию без конвертации. |
| [set_DestFileName](./set_destfilename/)(const System::String\&) | Устанавливает имя целевого файла. |
| [set_DestStream](./set_deststream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает целевой поток. |
| [set_ExportItems](./set_exportitems/)(const System::ArrayPtr\<System::ArrayPtr\<System::String\>\>\&) | Устанавливает параметры для комбобокса с экспортируемыми значениями. |
| [set_Facade](./set_facade/)(const System::SharedPtr\<FormFieldFacade\>\&) | Устанавливает визуальные атрибуты поля. |
| [set_Items](./set_items/)(const System::ArrayPtr\<System::String\>\&) | Устанавливает элементы, которые будут добавлены в только что созданный список или комбобокс. |
| [set_RadioButtonItemSize](./set_radiobuttonitemsize/)(double) | Устанавливает размер элемента радиокнопки (при добавлении нового поля радиокнопки). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField([FieldType.Radio](../fieldtype/), "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [set_RadioGap](./set_radiogap/)(float) | Член, фиксирующий промежуток между двумя соседними радиокнопками в пикселях, по умолчанию 50. |
| [set_RadioHoriz](./set_radiohoriz/)(bool) | Флаг, указывающий, расположены ли радиокнопки горизонтально или вертикально, значение по умолчанию — true. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Устанавливает объект Response, в котором будет сохранён результат операции. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Устанавливает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(const System::String\&) | Устанавливает имя исходного файла. |
| [set_SrcStream](./set_srcstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает исходный поток. |
| [set_SubmitFlag](./set_submitflag/)(SubmitFormFlag) | Устанавливает флаги отправки для кнопки submit. |
| [SetFieldAlignment](./setfieldalignment/)(const System::String\&, int32_t) | Устанавливает стиль выравнивания текстового поля. |
| [SetFieldAlignmentV](./setfieldalignmentv/)(const System::String\&, int32_t) | Устанавливает стиль вертикального выравнивания текстового поля. |
| [SetFieldAppearance](./setfieldappearance/)(const System::String\&, Annotations::AnnotationFlags) | Устанавливает флаги поля. |
| [SetFieldAttribute](./setfieldattribute/)(const System::String\&, PropertyFlag) | Устанавливает атрибуты поля. |
| [SetFieldCombNumber](./setfieldcombnumber/)(const System::String\&, int32_t) | Устанавливает количество ячеек (comb) для обычного однострочного текстового поля (поле автоматически делится на столько равноотстоящих позиций, или ячеек, сколько указано в параметре combNumber). |
| [SetFieldLimit](./setfieldlimit/)(const System::String\&, int32_t) | Устанавливает максимальное количество символов в текстовом поле. |
| [SetFieldScript](./setfieldscript/)(const System::String\&, const System::String\&) | Устанавливает JavaScript для поля PushButton. Если ранее существовал JavaScript, он будет заменён новым. |
| [SetSubmitFlag](./setsubmitflag/)(const System::String\&, SubmitFormFlag) | Устанавливает флаг отправки у кнопки submit. |
| [SetSubmitUrl](./setsubmiturl/)(const System::String\&, const System::String\&) | Устанавливает URL кнопки. |
| [Single2Multiple](./single2multiple/)(const System::String\&) | Преобразует однострочное текстовое поле в многострочное. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
