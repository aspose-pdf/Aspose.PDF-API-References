---
title: MoveField
second_title: Aspose.PDF для справочника API .NET
description: Установить новую позицию поля.
type: docs
weight: 240
url: /ru/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

Установить новую позицию поля.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое необходимо переместить. |
| llx | Single | Абсцисса нижнего левого угла поля. |
| lly | Single | Ордината нижнего левого угла поля. |
| urx | Single | Абсцисса правого верхнего угла поля. |
| ury | Single | Ордината правого верхнего угла поля. |

### Возвращаемое значение

true, если позиция поля была успешно изменена.

### Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->