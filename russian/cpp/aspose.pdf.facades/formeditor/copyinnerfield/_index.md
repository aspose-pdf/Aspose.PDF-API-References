---
title: "Aspose::Pdf::Facades::FormEditor::CopyInnerField method"
linktitle: "CopyInnerField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::FormEditor::CopyInnerField method. Копирует существующее поле в то же положение на указанной странице. Будет создан новый документ, который содержит всё, что есть в исходном документе, за исключением только что скопированного поля на C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.facades/formeditor/copyinnerfield/
---
## FormEditor::CopyInnerField(const System::String\&, const System::String\&, int32_t) method


Копирует существующее поле в то же положение на указанной странице. Будет создан новый документ, содержащий всё, что есть в исходном документе, за исключением только что скопированного поля.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(const System::String &fieldName, const System::String &newFieldName, int32_t pageNum)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Старое полностью квалифицированное имя поля. |
| newFieldName | const System::String\& | Новое полностью квалифицированное имя поля. Если null, оно будет установлено как fieldName + "~". |
| pageNum | int32_t | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |

## См. также

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyInnerField(const System::String\&, const System::String\&, int32_t, float, float) method


Копирует существующее поле в новое положение, указанное номером страницы и координатами. Будет создан новый документ, содержащий всё, что есть в исходном документе, за исключением только что скопированного поля.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(const System::String &fieldName, const System::String &newFieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Старое полностью квалифицированное имя поля. |
| newFieldName | const System::String\& | Новое полностью квалифицированное имя поля. Если null, оно будет установлено как fieldName + "~". |
| pageNum | int32_t | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |
| abscissa | float | Абсцисса нового поля. Если -1, абсцисса будет равна оригинальной. |
| ордината | float | Оордината нового поля. Если -1, ордината будет равна исходной. |

## См. также

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
