---
title: "Aspose::Pdf::Facades::FormEditor::AddField method"
linktitle: "AddField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::FormEditor::AddField method. Добавить поле указанного типа в форму в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.facades/formeditor/addfield/
---
## FormEditor::AddField(FieldType, const System::String\&, const System::String\&, int32_t, float, float, float, float) method


Добавить поле указанного типа в форму.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, const System::String &fieldName, const System::String &initValue, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | FieldType | Тип поля, которое должно быть добавлено. |
| fieldName | const System::String\& | Имя поля, которое должно быть добавлено. |
| initValue | const System::String\& | Начальное значение поля. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) номер, где должно быть размещено новое поле. |
| llx | float | Абсцисса нижнего левого угла поля. |
| lly | float | Ордината нижнего левого угла поля. |
| urx | float | Абсцисса верхнего правого угла поля. |
| ury | float | Ордината правого верхнего угла поля. |

### ReturnValue

true, если поле было успешно добавлено.
## Примечания



///
## См. также

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::AddField(FieldType, const System::String\&, int32_t, float, float, float, float) method


Добавить поле указанного типа в форму.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, const System::String &fieldName, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | FieldType | Тип поля, которое должно быть добавлено. |
| fieldName | const System::String\& | Имя поля, которое должно быть добавлено. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) номер, где должно быть размещено новое поле. |
| llx | float | Абсцисса нижнего левого угла поля. |
| lly | float | Ордината нижнего левого угла поля. |
| urx | float | Абсцисса верхнего правого угла поля. |
| ury | float | Ордината правого верхнего угла поля. |

### ReturnValue

true, если поле было успешно добавлено.

## См. также

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
