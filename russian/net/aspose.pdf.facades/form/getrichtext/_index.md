---
title: GetRichText
second_title: Aspose.PDF для справочника API .NET
description: Получить значение поля Rich Text включая информацию о форматировании каждого символа.
type: docs
weight: 290
url: /ru/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

Получить значение поля Rich Text, включая информацию о форматировании каждого символа.

```csharp
public string GetRichText(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля для поля Rich Text. |

### Возвращаемое значение

Возвращает строку, содержащую информацию о форматировании поля Rich Text.

### Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->