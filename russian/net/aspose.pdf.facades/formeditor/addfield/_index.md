---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Добавить поле указанного типа в форму
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Добавить поле указанного типа в форму.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | FieldType | Тип поля, которое должно быть добавлено. |
| fieldName | String | Имя поля, которое должно быть добавлено. |
| pageNum | Int32 | Номер страницы, на которой должно быть размещено новое поле. |
| llx | Single | Абсцисса нижнего левого угла поля. |
| lly | Single | Ордината нижнего левого угла поля. |
| urx | Single | Абсцисса верхнего правого угла поля. |
| ury | Single | Ордината верхнего правого угла поля. |

### Возвращаемое значение

true, если поле было успешно добавлено.

## Примеры

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### См. также

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Добавить поле указанного типа в форму.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | FieldType | Тип поля, которое должно быть добавлено. |
| fieldName | String | Имя поля, которое должно быть добавлено. |
| initValue | String | Начальное значение поля. |
| pageNum | Int32 | Номер страницы, на которой должно быть размещено новое поле. |
| llx | Single | Абсцисса нижнего левого угла поля. |
| lly | Single | Ордината нижнего левого угла поля. |
| urx | Single | Абсцисса верхнего правого угла поля. |
| ury | Single | Ордината верхнего правого угла поля. |

### Возвращаемое значение

true, если поле было успешно добавлено.

## Примеры

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### См. также

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)