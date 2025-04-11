---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Копирует существующее поле в то же положение на указанном номере страницы. Будет создан новый документ, который содержит все, что есть в исходном документе, за исключением вновь скопированного поля.
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Копирует существующее поле в то же положение на указанном номере страницы. Будет создан новый документ, который содержит все, что есть в исходном документе, за исключением вновь скопированного поля.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Старое полное имя поля. |
| newFieldName | String | Новое полное имя поля. Если null, оно будет установлено как fieldName + "~". |
| pageNum | Int32 | Номер страницы, на которой будет находиться новое поле. Если -1, новое поле будет скопировано на ту же страницу, на которой находится старое. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Копирует существующее поле в новое положение, указанное как номер страницы и координаты. Будет создан новый документ, который содержит все, что есть в исходном документе, за исключением вновь скопированного поля.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Старое полное имя поля. |
| newFieldName | String | Новое полное имя поля. Если null, оно будет установлено как fieldName + "~". |
| pageNum | Int32 | Номер страницы, на которой будет находиться новое поле. Если -1, новое поле будет скопировано на ту же страницу, на которой находится старое. |
| abscissa | Single | Абсцисса нового поля. Если -1, абсцисса будет равна оригинальной. |
| ordinate | Single | Ордината нового поля. Если -1, ордината будет равна оригинальной. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)