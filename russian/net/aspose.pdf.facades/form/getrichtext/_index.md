---
title: "Form.GetRichText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Получает значение поля Rich Text, включая информацию о форматировании каждого символа"
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

Получает значение поля Rich Text, включая информацию о форматировании каждого символа.

```csharp
public string GetRichText(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полностью квалифицированное имя поля Rich Text. |

### Возвращаемое значение

Возвращает строку, содержащую информацию о форматировании поля Rich Text.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


