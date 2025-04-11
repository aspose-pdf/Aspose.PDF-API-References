---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Измените однострочное текстовое поле на многострочное
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/formeditor/single2multiple/
---
## Метод FormEditor.Single2Multiple

Измените однострочное текстовое поле на многострочное.

```csharp
public bool Single2Multiple(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Квалифицированное имя поля. |

### Возвращаемое значение

Если успешно, возвращает true; в противном случае false.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)