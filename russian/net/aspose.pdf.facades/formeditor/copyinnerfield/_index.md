---
title: CopyInnerField
second_title: Aspose.PDF для справочника API .NET
description: Копирует существующее поле в ту же позицию на странице с указанным номером. Будет создан новый документ содержащий все что есть в исходном документе за исключением вновь скопированного поля.
type: docs
weight: 190
url: /ru/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Копирует существующее поле в ту же позицию на странице с указанным номером. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением вновь скопированного поля.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Старое полное имя поля. |
| newFieldName | String | Новое полное имя поля. Если значение null, оно будет установлено как fieldName + "~". |
| pageNum | Int32 | Номер страницы для хранения нового поля. Если -1, новое поле будет копировано на ту же страницу, что и старое. |

### Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Создает копию текстового поля на второй странице.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Копирует существующее поле в новую позицию, указанную номером страницы и ординатами. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением вновь скопированного поля.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Старое полное имя поля. |
| newFieldName | String | Новое полное имя поля. Если значение null, оно будет установлено как fieldName + "~". |
| pageNum | Int32 | Номер страницы для хранения нового поля. Если -1, новое поле будет копировано на ту же страницу, что и старое. |
| abscissa | Single | Абсцисса нового поля. Если -1, абсцисса будет равна исходной. |
| ordinate | Single | Ордината нового поля. Если -1, ордината будет равна исходной. |

### Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Создает копию текстового поля на второй странице.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->