---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Переименовывает поле. Подходит как для поля AcroForm, так и для поля XFA
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/form/renamefield/
---
## Метод Form.RenameField

Переименовывает поле. Подходит как для поля AcroForm, так и для поля XFA.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | старое имя поля |
| newFieldName | String | новое имя поля |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)