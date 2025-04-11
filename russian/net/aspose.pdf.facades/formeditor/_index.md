---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.FormEditor. Класс для редактирования форм, добавления/удаления полей и т.д.
type: docs
weight: 4330
url: /ru/net/aspose.pdf.facades/formeditor/
---
## Класс FormEditor

Класс для редактирования форм (добавления/удаления полей и т.д.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Конструктор для FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Инициализирует новый объект `FormEditor` на основе *документа*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Устанавливает формат PDF файла. Результирующий файл будет сохранен в указанном формате файла. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без конвертации. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Устанавливает параметры для комбинированного поля с экспортируемыми значениями. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Устанавливает визуальные атрибуты поля. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Устанавливает элементы, которые будут добавлены в вновь созданный список или комбинированное поле. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Получает или устанавливает размер элемента радиокнопки (когда добавляется новое поле радиокнопки). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Член для записи промежутка между двумя соседними радиокнопками в пикселях, по умолчанию 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Флаг, указывающий, расположены ли радиокнопки горизонтально или вертикально, значение по умолчанию - true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Устанавливает флаги отправки кнопки отправки |

## Методы

| Имя | Описание |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Добавляет поле указанного типа в форму. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Добавляет поле указанного типа в форму. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Добавляет JavaScript для поля PushButton. Если существует старое событие, новое событие добавляется после него. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Добавляет новый элемент в список. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Добавляет новый элемент с экспортируемым значением в существующее поле списка, только для комбинированного поля AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Добавляет кнопку отправки на форму. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Закрывает фасад. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Копирует существующее поле в то же положение на указанной странице. Будет создан новый документ, который содержит все, что есть в исходном документе, кроме вновь скопированного поля. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Копирует существующее поле в новое положение, указанное как номер страницы и координаты. Будет создан новый документ, который содержит все, что есть в исходном документе, кроме вновь скопированного поля. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Копирует существующее поле из одного PDF документа в другой документ с оригинальным номером страницы и координатами. Обратите внимание: только для полей AcroForm (исключая радиокнопки). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Копирует существующее поле из одного PDF документа в другой документ с указанным номером страницы и оригинальными координатами. Обратите внимание: только для полей AcroForm (исключая радиокнопки). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Копирует существующее поле из одного PDF документа в другой документ с указанным номером страницы и координатами. Обратите внимание: только для полей AcroForm (исключая радиокнопки). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Изменяет визуальные атрибуты всех полей в PDF документе. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Изменяет визуальные атрибуты всех полей с указанным типом поля. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Изменяет визуальные атрибуты указанного поля. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Удаляет элемент из поля списка. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Получает флаги поля. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Устанавливает новое положение поля. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Удаляет поле из формы. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Удаляет действие отправки поля. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Изменяет имя поля. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Сбрасывает все визуальные атрибуты на пустое значение. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Сбрасывает все визуальные атрибуты внутреннего фасада на пустое значение. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Сохраняет PDF документ в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Сохраняет PDF документ в указанный файл. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Устанавливает стиль выравнивания текстового поля. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Устанавливает вертикальный стиль выравнивания текстового поля. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Устанавливает флаги поля |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Устанавливает атрибуты поля. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Устанавливает количество комбинированных полей для обычного однострочного текстового поля (поле автоматически делится на столько же равномерно расположенных позиций, или комбов, сколько значение параметра combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Устанавливает максимальное количество символов текстового поля. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Устанавливает JavaScript для поля PushButton. Если старый JavaScript существовал, он будет заменен новым. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Устанавливает флаг отправки кнопки отправки. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Устанавливает URL кнопки. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Изменяет однострочное текстовое поле на многострочное. |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)