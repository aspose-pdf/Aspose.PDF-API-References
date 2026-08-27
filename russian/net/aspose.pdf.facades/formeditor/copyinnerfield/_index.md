---
title: "FormEditor.CopyInnerField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Копирует существующее поле в то же положение на указанном номере страницы. Будет создан новый документ, содержащий всё, что есть в исходном документе, за исключением только что скопированного поля"
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Копирует существующее поле в то же положение на указанном номере страницы. Будет создан новый документ, который содержит всё, что есть в исходном документе, за исключением только что скопированного поля.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Старое полностью квалифицированное имя поля. |
| newFieldName | String | Новое полностью квалифицированное имя поля. Если null, оно будет установлено как fieldName + "~". |
| pageNum | Int32 | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Создаёт копию текстового поля на второй странице.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Копирует существующее поле в новое положение, указанное номером страницы и координатами. Будет создан новый документ, который содержит всё, что есть в исходном документе, за исключением только что скопированного поля.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Старое полностью квалифицированное имя поля. |
| newFieldName | String | Новое полностью квалифицированное имя поля. Если null, оно будет установлено как fieldName + "~". |
| pageNum | Int32 | Номер страницы, на которой будет размещено новое поле. Если -1, новое поле будет скопировано на ту же страницу, что и старое. |
| абсцисса | Single | Абсцисса нового поля. Если -1, абсцисса будет равна исходной. |
| ордината | Single | Ордината нового поля. Если -1, ордината будет равна исходной. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Создаёт копию текстового поля на второй странице.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


