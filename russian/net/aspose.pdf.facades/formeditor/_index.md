---
title: "Класс FormEditor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.FormEditor. Класс для редактирования форм, добавления/удаления полей и т.д."
type: docs
weight: 4450
url: /ru/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Класс для редактирования форм (добавление/удаление полей и т.д.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Конструктор для FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Инициализирует новый объект `FormEditor` на основе *document*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Устанавливает формат PDF‑файла. Результирующий файл будет сохранён в указанном формате. Если это свойство не указано, файл будет сохранён в формате PDF по умолчанию без конвертации. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Устанавливает параметры для комбобокса с экспортными значениями. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Устанавливает визуальные атрибуты поля. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Устанавливает элементы, которые будут добавлены в только что созданный список или комбобокс. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Получает или устанавливает размер элемента радиокнопки (при добавлении нового поля радиокнопки). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Член, фиксирующий промежуток между двумя соседними радиокнопками в пикселях, по умолчанию 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Флаг, указывающий, расположены ли радиокнопки горизонтально или вертикально, значение по умолчанию — true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Установить флаги отправки кнопки submit |

## Методы

| Имя | Описание |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Добавить поле указанного типа в форму. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Добавить поле указанного типа в форму. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Добавить JavaScript для поля PushButton. Если существует старое событие, новое событие будет добавлено после него. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Добавляет новый элемент в список. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Добавить новый элемент с экспортным значением в существующее поле списка, только для поля комбобокса AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Добавить кнопку отправки в форму. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Закрывает фасад. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Копирует существующее поле в то же положение на указанном номере страницы. Будет создан новый документ, который содержит всё, что есть в исходном документе, за исключением только что скопированного поля. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Копирует существующее поле в новое положение, указанное номером страницы и координатами. Будет создан новый документ, который содержит всё, что есть в исходном документе, за исключением только что скопированного поля. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Копирует существующее поле из одного PDF‑документа в другой документ с оригинальным номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и оригинальными координатами. Примечание: только для полей AcroForm (исключая переключатели). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Копирует существующее поле из одного PDF‑документа в другой документ с указанным номером страницы и координатами. Примечание: только для полей AcroForm (исключая переключатели). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Изменяет визуальные атрибуты всех полей в PDF‑документе. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Изменяет визуальные атрибуты всех полей указанного типа. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Изменяет визуальные атрибуты указанного поля. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Удаляет элемент из поля списка. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Получить флаги поля. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Установить новое положение поля. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Удалить поле из формы. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Удалить действие отправки у поля. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Изменить имя поля. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Сбросить все визуальные атрибуты к пустому значению. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Сбросить все визуальные атрибуты внутреннего фасада к пустому значению. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Сохраняет PDF‑документ в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Сохраняет PDF‑документ в указанный файл. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Установить стиль выравнивания текстового поля. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Установить стиль вертикального выравнивания текстового поля. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Установить флаги поля |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Установить атрибуты поля. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Устанавливает количество ячеек (comb) для обычного однострочного текстового поля (поле автоматически делится на столько равноотстоящих позиций, или ячеек, сколько указано в параметре combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Устанавливает максимальное количество символов текстового поля. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Устанавливает JavaScript для поля PushButton. Если существовал старый JavaScript, он будет заменён новым. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Устанавливает флаг отправки для кнопки submit. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Устанавливает URL кнопки. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Преобразует однострочное текстовое поле в многострочное. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


