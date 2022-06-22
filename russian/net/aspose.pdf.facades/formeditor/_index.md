---
title: FormEditor
second_title: Aspose.PDF для справочника API .NET
description: Класс для редактирования форм добавление/удаление полей и т.п.
type: docs
weight: 2340
url: /ru/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Класс для редактирования форм (добавление/удаление полей и т.п.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FormEditor](formeditor#constructor)() | Конструктор для FormEditor. |
| [FormEditor](formeditor#constructor_1)(Document) | Инициализирует новый[`FormEditor`](../formeditor)объект на основе*document*. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | Получает или задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | Получает или задает способ сохранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение:inline/attachment. По умолчанию:встроенный. |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, то файл будет сохранен в формате PDF по умолчанию без преобразования. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | Устанавливает параметры для поля со списком с экспортируемыми значениями. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | Устанавливает визуальные атрибуты поля. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | Устанавливает элементы, которые будут добавлены в только что созданный список или поле со списком.  &lt;code&gt; formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf"); formEditor.Items = new string[] { "AAA", "BBB", "CCC" }; formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.Save(); &lt;/code&gt; |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | Получает или устанавливает размер элемента переключателя (при добавлении нового поля переключателя). &lt;code&gt; formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "Первый", "Второй", "Третий" }; formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Второй", 1, 10, 30, 110, 130); formEditor.Save(); &lt;/code&gt; |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | Элемент для записи промежутка между двумя соседними переключателями в пикселях, по умолчанию 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | Флаг, указывающий, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию равно true. |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | Получает или задает объект Response, в котором будет храниться результат операции. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию:PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | Установите флаги отправки кнопки отправки |

## Методы

| Имя | Описание |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | Добавить на форму поле указанного типа. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | Добавить на форму поле указанного типа. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | Добавить JavaScript для поля PushButton. Если старое событие существует, новое событие добавляется после него. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | Добавляет новый элемент в список. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | Добавить новый элемент со значением экспорта в существующее поле списка, только для поля со списком AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | Добавить кнопку отправки на форму. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | Закрывает фасад. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | Копирует существующее поле в ту же позицию на указанной странице. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением только что скопированного поля. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | Копирует существующее поле в новую позицию, указанную номером страницы и координатами. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением только что скопированного поля. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | Копирует существующее поле из одного документа PDF в другой документ с исходным номером страницы и ординатами. Примечание:Только для полей AcroForm (за исключением переключателя). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и исходными ординатами. Примечание:Только для полей AcroForm (за исключением переключателя). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и координатами. Примечание:Только для полей AcroForm (за исключением переключателя). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | Изменяет визуальные атрибуты всех полей в документе PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | Изменяет визуальные атрибуты всех полей с указанным типом поля. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | Изменяет визуальные атрибуты указанного поля. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | Удалить элемент из поля списка. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | Получить флаги полей. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | Установить новую позицию поля. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | Удалить поле из формы. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | Удалить действие отправки поля. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | Изменить имя поля. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | Сбросить все визуальные атрибуты до пустого значения. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | Сбросить все визуальные атрибуты внутреннего фасада до пустого значения. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Сохраняет документ PDF в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Сохраняет документ PDF в указанный файл. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | Установить стиль выравнивания текстового поля. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | Установить стиль вертикального выравнивания текстового поля. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | Установить флаги полей |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | Установить атрибуты поля. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | Устанавливает количество гребенок для обычного однострочного текстового поля (поле автоматически делится на столько же равноотстоящих позиций, или гребенок, как значение параметра combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | Устанавливает максимальное количество символов в текстовом поле. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | Установите JavaScript для поля PushButton. Если старый JavaScript существовал, он будет заменен новым. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | Установить флаг отправки кнопки отправки. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | Устанавливает URL кнопки. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | Изменить однострочное текстовое поле на многострочное. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
