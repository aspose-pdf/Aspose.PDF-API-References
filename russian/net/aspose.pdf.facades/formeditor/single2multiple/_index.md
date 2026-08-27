---
title: "FormEditor.Single2Multiple"
second_title: "Справочник API Aspose.PDF для .NET"
description: "метод FormEditor. Преобразовать однострочное текстовое поле в многострочное"
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Преобразует однострочное текстовое поле в многострочное.

```csharp
public bool Single2Multiple(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное (квалифицированное) имя поля. |

### Возвращаемое значение

Если успешно, возвращает true; иначе false.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


