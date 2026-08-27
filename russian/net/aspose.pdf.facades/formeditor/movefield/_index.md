---
title: "FormEditor.MoveField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Устанавливает новое положение поля"
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

Установить новое положение поля.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое необходимо переместить. |
| llx | Single | Абсцисса нижнего левого угла поля. |
| lly | Single | Ордината нижнего левого угла поля. |
| urx | Single | Абсцисса верхнего правого угла поля. |
| ury | Single | Ордината верхнего правого угла поля. |

### Возвращаемое значение

true, если позиция поля была успешно изменена.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


