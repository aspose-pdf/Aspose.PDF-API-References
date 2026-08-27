---
title: "Form.RenameField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Переименовывает поле. Подойдёт как поле AcroForm, так и поле XFA."
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

Переименовывает поле. Подходит как поле AcroForm, так и поле XFA.

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


